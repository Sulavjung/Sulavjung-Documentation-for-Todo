### User Flow for TodoToday App

1. **Start Screen**
    - Checks Previous Logged In Status 
        - If logged in, Dashboard
        - If not logged in, user is taken to the login page. 
            - Log In
2. **Log In**
    - User is prompted to enter:
        - Email or Username
        - Password
    - User selects "Log In" button.
        - If credentials are valid, the user is redirected to the Dashboard.
        - If credentials are invalid, the user is shown an error message and can try again or reset their password.
    - If user isn't registered user, user will choose to Register
3. **Register**
    - User is prompted to enter:
        - Username
        - Email
        - Password
        - Confirm Password
        - Agree to Terms and Conditions (checkbox)
    - User selects "Register" button.
        - If successful, successful message is shown and the user is redirected to the Log In screen.
        - If there are issues (e.g., email already in use), the user is shown an error message and asked to try again.
4. **Dashboard (After Login)**
    - User views an overview of tasks:
        - Today’s tasks
        - Upcoming tasks
        - Overdue tasks
        - Lists of tasks
        - Tasks with priorities.
    - Navigation options include:
        - Create Task
        - View Tasks
        - Account Settings
        - Log Out
5. **Create Task**
    - User selects "Create Task".
    - User is prompted to enter task details:
        - Title/Description
        - Due Date and Time
        - Categories (User can select from existing categories or create a new one)
        - Priority (Low, Medium, High)
        - Reminder Settings
    - User submits the task.
        - The app confirms the creation of the task.
        - Updates the task to the list where it is supposed to be.
        - The user is redirected back to the Dashboard or to the list of tasks.
6. **View Tasks**
    - User selects "View Tasks".
    - User is presented with a list of tasks, which can be filtered or sorted by: `Yet to be confirmed`
        - Due Date
        - Priority
        - Category
    - For each task, the user can:
        - Edit Task
        - Mark as Completed
        - Delete Task
7. **Edit Task**
    - From the list of tasks, the user selects a task to edit.
    - User is presented with the current task details and can modify:
        - Title/Description
        - Due Date and Time
        - Categories
        - Priority
        - Reminder Settings
    - User submits the changes.
        - The app confirms the update.
        - The user is redirected back to the list of tasks.
8. **Account Settings**
    - User selects "Account Settings".
    - User can update:
        - Profile Information (Username, Email)
        - Change Password
    - User can also:
        - Log Out
        - Delete Account
9. **Log Out**
    - From any screen, the user selects "Log Out".
    - The app confirms the action.
    - The user is redirected to the Start Screen.
