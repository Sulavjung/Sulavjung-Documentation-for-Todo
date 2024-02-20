# Todo - Application
Here are some of the main data items and entities. 
****
### 1. Task:
   - **Meaning:** Since it is a todo app, it should have at least a task. It represents an activity or item that needs to be completed.
   - **Usage:** Users can create, view, edit, and delete tasks within the application.
   - **Data Structure:** Contains fields such as task ID, description, due date, priority, status, associated user ID and many more.

### 2. User:
   - **Meaning:** Users are anyone who will be using the application. 
   - **Usage:** Users can register, login, and manage their tasks.
   - **Data Structure:** Includes fields like username, email, password, and possibly additional profile information.

### 3. Project:
   - **Meaning:** Groups tasks together under a common theme or goal. This could be something that is interchangeable to tasks. If the task itself has child task, it should be project. `Yet to be confirmed with team.`
   - **Usage:** Helps organize tasks and allows users to focus on specific objectives.
   - **Data Structure:** Consists of a name, description, and possibly a list of associated tasks.

### 4. Category:
   - **Meaning:** Classifies tasks into different types or categories. User is the one categorizing the tasks. 
   - **Usage:** Aids in organizing tasks based on their nature or purpose.
   - **Data Structure:** Contains a name and possibly a description.

<img width="1128" alt="Pasted image 20240215145021" src="https://github.com/Sulavjung/Sulavjung-Documentation-for-Todo/assets/79497159/3c1c77cf-5545-43bd-9e49-cf20f4078fb7">

---
## Few More: 
There are not so important items that in itself aren't data items but does consist of categorical data. 

### 1. Priority:
   - **Meaning:** Indicates the level of importance or urgency assigned to a task.
   - **Usage:** Helps users prioritize their tasks and focus on what needs to be done first.
   - **Data Structure:** Typically includes levels such as high, medium, and low, each associated with a corresponding value or weight.

### 2. Status:
   - **Meaning:** Reflects the current state or progress of a task.
   - **Usage:** Allows users to track the status of their tasks, whether they are pending, in progress, or completed.
   - **Data Structure:** Includes options like pending, in progress, completed, or archived.

### 3. Percentile:
   - **Meaning:** Shows the completion percentage of tasks or projects.
   - **Usage:** Provides users with a visual representation of their progress and helps them stay motivated.
   - **Data Structure:** Represents the percentage of completed tasks relative to the total number of tasks in a project or category.

### 4. Deadline:
   - **Meaning:** Specifies the date and time by which a task should be completed.
   - **Usage:** Helps users stay organized and meet their deadlines effectively.
   - **Data Structure:** Contains fields for the due date and possibly the time of day.
