# User API's
---
## 1. Endpoint: `/users/register`

This endpoint allows users to register with the system.


| Parameter    | Type     | Description                                                        |
|--------------|----------|--------------------------------------------------------------------|
| `username`   | string   | The username of the user. Required.                                |
|              |          | - Must begin with a letter ([a-zA-Z]).                             |
|              |          | - Should have 3 or more alphanumeric characters.                  |
| `email`      | string   | The email address of the user. Required.                           |
|              |          | - Must be a valid email format.                                    |
| `password`   | string   | The password chosen by the user. Required.                         |
|              |          | - Must include at least 1 uppercase letter, 1 number, 1 special character.|
|              |          | - Should have a minimum length of 8 characters.                    |
| `agreeTerms` | boolean  | User's consent to terms. Required.                                 |

##### Example Usage:

```http
POST /users/register
Host: http://52.52.61.214
Content-Type: application/json

{
  "username": "example_user",
  "email": "user@example.com",
  "password": "example_password",
  "agreeTerms": true
}
```

##### Example Response:

```json
{
  "success": true,
  "message": "You successfully created your account.",
  "redirectTo": "/login"
}
```

---

## 2. Endpoint: `/users/login`

This endpoint allows users to log in to their account.

| Parameter  | Type   | Description                             |
|------------|--------|-----------------------------------------|
| `username` | string | The username of the user. Required.     |
| `password` | string | The password of the user. Required.     |

##### Example Usage:

```http
POST /users/login
Host: http://52.52.61.214
Content-Type: application/json

{
  "username": "example_user",
  "password": "example_password"
}
```

##### Example Response:

```json
{
  "success": true,
  "message": "You are successfully logged in.",
  "redirectTo": "/",
  "userId": 123,
  "username": "example_user",
  "email": "user@example.com"
}
```

---

## 3. Endpoint: `/users/logout`

This endpoint allows users to log out of their account.

##### Example Usage:

```http
POST /users/logout
Host: http://52.52.61.214
Content-Type: application/json
```

##### Example Response:

```json
{
  "success": true,
  "message": "You are successfully logged out.",
  "redirectTo": "/"
}
```

---
---
# Team

## 1. Endpoint: `/team`

This endpoint retrieves team data.

##### Method:
- `GET`

##### Description:
This endpoint retrieves data for all teams.

##### Example Usage:

```http
GET /team
Host: http://52.52.61.214
```

##### Example Response:

```json
[
  {
    "team_id": 1,
    "team_name": "Team A",
    "team_lead": "John Doe",
    "members": ["Alice", "Bob", "Charlie"]
  },
  {
    "team_id": 2,
    "team_name": "Team B",
    "team_lead": "Jane Smith",
    "members": ["David", "Eva", "Frank"]
  }
]
```

In this example, the API endpoint `/team` is called with a `GET` request, and the response contains an array of team objects with details such as team ID, team name, team lead, and team members.

---
---
# Tasks

## 1. Endpoint: `/tasks/`

This endpoint retrieves tasks for the logged-in user.

##### Method:
- `GET`

##### Middleware:
- `isLoggedIn`: User authentication middleware

##### Description:
This endpoint retrieves tasks associated with the logged-in user.

##### Example Usage:

```http
GET /tasks/
Host: example.com
```

##### Example Response:

```json
{
  "tasks": [
    {
      "taskID": 1,
      "name": "Task 1",
      "description": "Description of Task 1",
      "dueDateTime": "2024-04-02T10:00:00Z",
      "priority": "High",
      "status": "In Progress",
      "percentCompleted": 50,
      "listID": 1,
      "userID": 123
    },
    {
      "taskID": 2,
      "name": "Task 2",
      "description": "Description of Task 2",
      "dueDateTime": "2024-04-03T15:00:00Z",
      "priority": "Medium",
      "status": "Pending",
      "percentCompleted": 25,
      "listID": 2,
      "userID": 123
    }
  ]
}
```

---

## 2. Endpoint: `/tasks/search`

This endpoint allows users to search for tasks based on a keyword.

##### Method:
- `GET`

##### Middleware:
- `isLoggedIn`: User authentication middleware

##### Parameters:
- `key` (string, required): The keyword to search for.

##### Description:
This endpoint searches for tasks associated with the logged-in user based on the provided keyword.

##### Example Usage:

```http
GET /tasks/search?key=keyword
Host: example.com
```

##### Example Response:

```json
{
  "count": 2,
  "tasks": [
    {
      "taskID": 1,
      "name": "Task 1",
      "description": "Description of Task 1",
      "dueDateTime": "2024-04-02T10:00:00Z",
      "priority": "High",
      "status": "In Progress",
      "percentCompleted": 50,
      "listID": 1,
      "userID": 123
    },
    {
      "taskID": 3,
      "name": "Task 3",
      "description": "Description of Task 3",
      "dueDateTime": "2024-04-04T12:00:00Z",
      "priority": "Low",
      "status": "Completed",
      "percentCompleted": 100,
      "listID": 1,
      "userID": 123
    }
  ]
}
```

---

In these examples, the API endpoints `/tasks/` and `/tasks/search` are utilized for retrieving tasks and searching for tasks respectively. The endpoints are protected by the `isLoggedIn` middleware to ensure authentication. The responses contain task data in JSON format.
