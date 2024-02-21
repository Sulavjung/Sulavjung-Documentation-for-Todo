SW Engineering CSC648-848-05 Fall 2024 

Project Title: ToDo-Today (WIP)  

Team: 02

Names of Group Members:

| Name             | Email                 | Role      |
| ---------------- | --------------------- | --------- |
| Alex Nikols      | anikols@mail.sfsu.edu | Team-Lead |
| Jason Tran       |                       |        Front-Lead   |
| Sulav Jung Hamal |                       |      Backend-Lead     |
| Jadon Hoang      |                       |     Github Master      |
| Randale Reyes    |                       |           |
| Christian Gopez  |                       |    Docs Master       |

Date: 02/15/2024

| Date       | Revision         |
| ---------- | ---------------- |
| 2/15/2024  | Created Document |
| 02/19/2024 | Added 1-7 from checkpoint 1                 |

---
## I. Brainstorming Ideas 
### 1. Dungeon Finder:
An application similar to a dating app but for people, Dungeons and Dragons players. Using this app people who are looking for a group to play with would be able to connect with others. Users would be able to fill out a profile consisting of things such as the type of player they are, their character information, and also what they are looking for in a group.

Pros:  
- An easy way for players to find a group.

Cons:
- 

### 2. ToDoToday (WIP):
A ToDo list that is able to support the ability to mark down a certain degree of percentage done for a task. The idea of not being able to mark down a task as done is demoralizing to the person and doesn't help in productivity. With this feature, we are able to make sure that we can keep track of and visualize the progress that we are making in the tasks that we mark down. There will also be a journal feature that can help the users to reflect and further digest how they are doing for a task.

Pros:
- Providing a motivating way for marking tasks off
- Journalling feature to help reflect on tasks

Cons: 
- Many other competitors. 
- ?

### 3. RentABook
Textbook rental service similar to that of Airbnb. We all have been in a position where either we do not have the funds to get a new textbook that is required for a class that we are taking or we bought a textbook and no longer have a use for it rendering it useless. This app fixes both of these problems because on this app you would be able to rent textbooks that you would need without having to pay the full price of that textbook. On the other hand, you would also be able to put the textbook that you have up for rent so that you can make money off of a book that you might not have a use for anymore.

Pros:
- Can help provide texts and education for cheaper prices
- Can be another income source for those with old textbooks

Cons:  
- Legality?
- Would be hard to monitor and make sure the textbook owners do not get scammed

## II. Executive Summary
TODo TODay is a To-Do List and daily task tracker app, with integrated calendar and journaling functions. What makes the TODo TODay app stand out are a couple of unique twists on the classic To Do List apps currently available on the market. The first of which is the ability to allow for partial completion of tasks and to mark them by percentage. This task system is also embedded into a nesting structure allowing for smaller tasks to be nested inside of larger tasks so you can understand your overall progress on projects or daily goals cleanly and intuitively. The other unique addition to this sort of To Do List app is a dynamic journaling function. This dynamic journal will use an AI GPT system to dynamically create new journal prompts for the user daily based on what is the highest priority on their current to-do list.

TODo TODay is specifically designed to be an easy-to-use way of organizing anything from an individual's small tasks in their daily life to massive projects that may take months or years to complete. The reason why my team and I decided to create TODo TODay was to look into every other To Do List app and how they work. Every single application that we found was binary either the task was complete or it wasn't. This kind of binary choice can be very demoralizing for large projects and does not give you an overall understanding of your progress. We created this app to take the best parts of large project trackers that are used in the industry and bring them to a more public audience. As well as including tasks and tools to help users stay on track with their projects and make sure that they have enough time to get everything done.

TODo TODay‘s flexibility and structure helps reinforce the habit of maintaining and updating their to-do list while also clearing off tasks from it. This positive reinforcement loop will not only help users be on top of all the regularly scheduled things they may need to do in their regular lives but also allow them to find time for themselves. The other thing TODo TODay will do is encourage the user to journal their experience and where they might be struggling with their tasks it will help them engage more fully in thinking about what they might be struggling with and how they might improve over time. Say somebody has practice guitar as a regular task they do weekly, then TODo TODay will bring that up in the journal and have the user talk about how they feel they are progressing in their guitar practice. When the user interacts and journal their experience it will help them crystallize and coalesce their feelings on how the practice has been going and how they have been doing which will help them better understand what they can do to keep improving and getting better at playing the guitar. This is just one example of the type of positive reinforcement and benefit you get out of the journaling and reevaluation process that TODo TODay is built around.

## III. Main Use Case
### 1. Student managing their schedule
- Actor: Student
- Assumptions:
	- The student has access to the internet. 
	- The student has access to a device (phone or laptop)
- Use Case: 
  This student is very busy, they are taking a heavy workload this semester and must have a way to organize and complete these tasks on time. Stressed out and anxious, the student decides to download an app (ToDoToday) on their phone In one of the courses, the student has been assigned a large project with multiple milestones and checkpoints.
- Benefits: 
	- Organization: The information and tasks are easily available for the student to see and manipulate
	- Progress Tracking: The student can have a visual representation of tasks completed for the day and could have an idea of how much more is left to do.
- Potential Requirements: 
	- Nested Scheduling: The ability to have different lists that can be easily differentiable from one another. Maybe being able to name certain lists. 
	- Task Percentage: Rather than fully checking off a task, provide a feature where they can check a certain amount of percentage and also be able to display the progress bar to the user.
![Pasted image 20240221075323](https://github.com/Sulavjung/Sulavjung-Documentation-for-Todo/assets/79497159/5becbe0b-0a37-4c11-903d-fe85e0283665)

### 2. A mother trying to manage both their kid's differing schedule and varying tasks
- Actor: Parents
- Assumptions:
  - Parents have access to the internet
  - Parents have access to a device (phone or laptop)
- Use Case:
  A mother is having a hard time trying to keep track of her children’s schedules throughout the school year due to them being in different extracurriculars. One of the kids is more athletic and is involved in more sports and physical activities. The other child is more into music and computers. The two children have varying schedules and the mother needs a way to schedule and organize them. This app will help keep the two schedules separate for easier viewing. Within these sub-lists, she will be able to list the different things she has lined up for the specific child. As she gets things done the progress percentage will reflect and show how many of the activities or tasks were completed for that child's schedule. There will also be a feature that the mother can use to mark certain tasks to be more important so that she would know which task she would have to focus on more at that time. Lastly, the journal feature will be able to give her time to reflect on the tasks done, what she could have done better, and overall reflect on her day.
- Benefits:
  - Organization: The information and tasks are easily available for the mother to see and manipulate
  - Progress Tracking: The mother can have a visual representation of tasks completed for the day and could have an idea of how much more is left to do.
  - Motivation: Rather than giving up, the journal will help with the ability to contemplate what she has done so far if things are a little overwhelming she be able to contemplate what to for next time.
- Potential Requirements:
  - Nested Scheduling: The ability to have different lists that can be easily differentiable from one another. Maybe being able to name certain lists
  - Task Percentage: Rather than fully checking off a task, provide a feature where they can check a certain amount of percentage and also be able to display the progress bar to the user.
  - Priority Setting: A feature to set the priority status of a task. This would allow people to set more important tasks to have a higher priority vs the lesser priority ones.
![Pasted image 20240221075347](https://github.com/Sulavjung/Sulavjung-Documentation-for-Todo/assets/79497159/ec9ffdd8-cab2-4154-a586-aad738c0bf92)


### 3. Patients utilizing the app to keep track and log their daily life
- Actor: Patients, Life Coach
- Assumptions:
  - Patients have access to the internet
  - Patients have access to a device (phone or laptop)
- Use Case:
  A life coach is helping patients day by day to help control and improve their patients lives. The life coach patient wants to have an app that would help them schedule their life schedules and tasks while also keeping track of their progress. The patient will be able to use the to-do list app to make lists of tasks needing their completion. They would also be able to set up subtasks to break down larger tasks to make them more manageable and less overwhelming. They can use the calendar to not only keep track of scheduled appointments but also to manage their time throughout the week. They also would then also be able to use the function of the journal app to keep tabs on how they are doing. The journal app will be a great feature for them as they would also be able to read and use the talking points they talked about in the journal section to their life coach and they would be able to debrief on the patient's week or day easier. With the addition of the progress bar the completion of tasks is no longer demoralizing but rather makes it motivating to get the percentage of the bar to 100.
- Benefits:
  - Self-Reflection: Through the journal app, the patient will be able to keep track of not only themselves but also the tasks they need to do through the app
  - Progress Tracking: The patient can have a visual representation of tasks completed for the day and could have an idea of how much more is left to do.
  - Motivation: The visualization of the progress bar will be motivating to the patient to be able to get their tasks done.
- Potential Requirements:
  - Nested Scheduling: The ability to have different lists that can be easily differentiable from one another. Maybe being able to name certain lists
  - Task Percentage: Rather than fully checking off a task, provide a feature where they can check a certain amount of percentage and also be able to display the progress bar to the user.
  - Priority Setting: A feature to set the priority status of a task. This would allow people to set more important tasks to have a higher priority vs the lesser priority ones
  - Journal feature: This feature will help the user debrief and think about the tasks that they are doing. Essentially having a recap and potentially being able to think about what worked for them and what didn't. Could also have a part where they keep track of their results or progress on tasks.
![Pasted image 20240221075412](https://github.com/Sulavjung/Sulavjung-Documentation-for-Todo/assets/79497159/8dfb2eea-5dba-45a1-838a-81d875366d3a)


### 4. Project Manager and Members using the app to organize tasks for the project
- Actor: Project Manager
- Assumptions:
  - The Project Manager has access to the internet
  - The Project Manager has access to a device (phone or laptop)
- Use Case:
  The project manager needs to lead multiple teams to develop a new software project. These teams need to work in harmony if they want to succeed in building this project. By using the ToDoToday app the project manager starts to create different files for multiple teams and in these files the manager creates main tasks for each team to work on and subtasks to follow. Since each of these main tasks need to be completed by a certain due date in order for another team to move forward, the manager adds these dates to his calendar. This allows for the product manager to manage each team in a much more efficient and organized manner. As each team is completing their subtasks, the manager checks off what has been completed, gradually increasing the progress bar for the main project. Overall, the organization allows the project manager to keep up with deadlines and pinpoint which tasks teams need to focus on in order to work in unison.
- Benefits:
  - Organization: The Employees or project members can make different lists for their tasks which could also have subtasks to break down the tasks even more.
  - Task Percentage: The Task Percentage will be helpful in that there is a visualization of how much the task has been done.
  - Priority Setting: Being able to choose which things are more urgent than others will be of help wot make sure that the things that need to be done are done before moving on in their project.
- Potential Requirements:
  - Nested Scheduling: The ability to have different lists that can be easily differentiable from one another. Maybe being able to name certain lists
  - Task Percentage: Rather than fully checking off a task, provide a feature where they can check a certain amount of percentage and also be able to display the progress bar to the user.
  - Priority Setting: A feature to set the priority status of a task. This would allow people to set more important tasks to have a higher priority vs the lesser priority one.
![Pasted image 20240221075434](https://github.com/Sulavjung/Sulavjung-Documentation-for-Todo/assets/79497159/93faa270-ca65-4f73-8a8a-a61eb6edab81)


### 5. Teachers using the app to plan their lessons for the different subjects that they are teaching
- Actor: Teacher
- Assumptions:
  - The Teacher has access to the internet
  - The Teacher has access to a device (phone or laptop)
- Use Case:
  The teacher is planning on teaching multiple sections of courses varying in different subjects. With the app, they would be able to list out specific tasks and lists for that specific class. Keeping the different to-do lists organized and sectioned for readability. They would be able to make different sub-lists pertaining to subjects such as math, science, and history. They would be able to have the lesson plan and then another list under that for checking off the material and steps on that lesson plan. Then depending on how the different subjects went the teacher would be able to log the lesson and talk about the things that she liked or things that she could improve on using the journal function of the app. If there is an important thing that is going on in a specific class such as one of them having a quiz or a test on a certain day, they would be able to mark that quiz or test as a high priority so that it is not missed. And using the calendar the teacher will be able to keep track of when quizzes, exams and other class milestones are approaching to make sure that she is keeping up with the schedule that she has laid out for the class.
- Benefits:
  - Organization: The Teacher can have separate lists for their needs. Through this, they have multiple to-do lists that they can easily access and find
  - Task Percentage: The Task Percentage will be helpful in that there is a visualization of how much the task has been done. They would also be able to see how much of the lesson plan they did by looking at the percentage of that task’s bar.
  - Priority Setting: Being able to choose which things are more urgent than others will be of help to make sure that important things are not forgotten.
- Potential Requirements:
  - Nested Scheduling: The ability to have different lists that can be easily differentiable from one another. Maybe being able to name certain lists
  - Task Percentage: Rather than fully checking off a task, provide a feature where they can check a certain amount of percentage and also be able to display the progress bar to the user.
  - Priority Setting: A feature to set the priority status of a task. This would allow people to set more important tasks to have a higher priority vs the lesser priority ones
  - Reminders: For really important or even just designated tasks there should be a way to have a reminder or a notification pop up to remind the user of that task
  - Easy UI: The user interface should be easy to use and easy to find the different lists without looking too cluttered.
![Pasted image 20240221075454](https://github.com/Sulavjung/Sulavjung-Documentation-for-Todo/assets/79497159/cea97971-2c0b-43fe-b91b-52483cbff47d)


### 6. A Traveler planning their trip and preparations
- Actor: Traveler
- Assumptions:
  - The traveler has access to the internet
  - The traveler has access to a device (phone or laptop)
- Use Case:
  Sarah is planning a vacation to Europe. She uses the app to create a packing list with items such as clothes, toiletries, and travel documents. As she packs each item, she checks it off in the app. She could see the completion rate of each place and uniquely identify which place she still needed to visit.
- Benefits:
  - Organization: It is easy for Sarah to make a list to track things such as things to pack. She can make lists of any of her needs during the trip through the app
  - Tracking: The lists that she makes can display the progress that she has made so that she can visually see how much else she has to pack, or how many more things she has to do in a certain city.
  - Planning: The app will make her planning easier and more accessible through the ability to create, change, and manage the different lists available through the app.
- Potential Requirements:
  - Nested Scheduling: The ability to have different lists that can be easily differentiable from one another. Maybe being able to name certain lists
  - Task Percentage: Rather than fully checking off a task, provide a feature where they can check a certain amount of percentage and also be able to display the progress bar to the user.
  - Priority Setting: A feature to set the priority status of a task. This would allow people to set more important tasks to have a higher priority vs the lesser priority ones
  - Reminders: For really important or even just designated tasks there should be a way to have a reminder or a notification pop up to remind the user of that task
  - Easy UI: The user interface should be easy to use and easy to find the different lists without looking too cluttered.
  - Manageability: The user should be able to manage and change things such as priority status and other general things like the name of the task or where the task is.
![Pasted image 20240221075520](https://github.com/Sulavjung/Sulavjung-Documentation-for-Todo/assets/79497159/c102c0a3-f3ac-48a4-8937-f6fb35e1aa3d)


### 7. Hobbyist working on multiple small side projects/models.
- Actor: Hobbyist
- Assumptions:
  - The hobbyist has an Internet connection
  - The hobbyist has access to a phone or laptop
- Use Case:
  This hobbyist is attempting to build a bookshelf in their workshop. They heard about a to-do list app from one of their friends for managing projects. He decides to download the app (ToDo ToDay). He then makes a new to-do list using the app to organize his bookshelf building project. He then set up the main task for that to do list first being researching the type of bookshelf he wants to build. Then he creates his first task, research. Next he creates subtasks for researching styles of bookshelves, researching materials, and researching the hardware he is going to use. He quickly decides to use the hardware he has on hand and gets that first subtask done then he moves on to research materials. He finds a deal on walnut wood and decides that that will be the material he’ll use for the project. Moving over to one of the other tasks, the purchase of materials, he goes down to the purchase, the wood for the body section and marks it off. He continues down the to-do list marking off tasks, building and setting everything up until he has everything ready for the bookshelf. He starts building the outside frame first and gets that done the first day. He marks that off his list and sees that he only has the shelves and the backside of the shelf to do next so he’s already 68% of the way through his project. Feeling more confident he continues to built the body of the bookshelf and now he is closer to 85% completion, all that’s left is finishing that up and then doing the final stages of staining and putting in hardware is able to check off everything from the list and it shows his completion at 100%. Once he is finished he then uses the Journal to reflect on what he struggled with and how he can improve for his next project.
- Benefits:
  - Organization: Easily break down your projects into smaller, manageable tasks.
  - Progress Tracking: The percentile completion allows you to gauge your overall progress at a glance.
  - Prioritization: Quickly identify and focus on tasks that need attention, ensuring efficient use of your time.
  - Flexibility: As you juggle multiple projects, adapt and prioritize tasks based on changing circumstances.
  - Motivation: Seeing progress percentages can be motivating and help you stay on track with your hobby projects
- Potential requirements:
  - Nested Task Management: The app should support the creation of hierarchical task structures, allowing users to break down larger projects into smaller, more manageable subtasks.
  - Task Percentage Completion: The app needs to have a feature that allows users to assign and visualize completion percentages for each task, providing a quick overview of the overall progress.
  - Prioritization: There should be functionality for users to prioritize tasks within a project, helping them focus on what needs immediate attention.
  - Flexibility and Adaptability: The app should allow users to easily modify and rearrange tasks as project requirements change or evolve over time.
  - Multi-Project Support: Since the hobbyist is working on multiple small projects simultaneously, the app should enable users to organize and switch between different projects efficiently.
  - Access Across Devices: Given the availability of a laptop and phone, the app should have synchronization capabilities, ensuring that the user can access and update their tasks seamlessly across various devices.
  - User-Friendly Interface: The app should provide an intuitive and user-friendly interface to enhance the overall user experience, making it easy for the hobbyist to manage tasks without a steep learning curve.
  - Motivational Features: Including visual elements or notifications that celebrate task completion milestones could contribute to a more motivating user experience.
![Pasted image 20240221075546](https://github.com/Sulavjung/Sulavjung-Documentation-for-Todo/assets/79497159/c6732269-b944-43dd-b15d-782c4004bd5c)


### 8. A zoo keeper keeps an eye on and maintains different species of animals in the zoo using the app to keep track of each enclosure.
- Actor: Zoo-Keeper
- Assumptions:
  - The Zoo-Keeper has access to the internet
  - The Zoo-Keeper has access to a device (phone or laptop)
- Use Case:
  Zookeeper was overwhelmed when trying to care for and keep track of the dietary and other needs of all of the different animals that were under his care. He found an app called todo today, that allowed him to set tasks for each animal that he had to take care of and under that task it set subtasks for their dietary requirements and any other task that he might need to do for each individual animal. This app was very convenient for him because it allowed him to not only keep track of feeding schedules using their calendar but also the percentage of completion of taking care of each animal during his shift. He uses the journaling function to keep track of the animals preferences for what they eat and other quirks. His Journal becomes a record for how to handle each animal. With the app he's found his job significantly more enjoyable and a lot less stressful as he does not have to worry about getting confused and either doing tasks twice or missing tasks.
- Benefits:
  - Organization: Easily break down your projects into smaller, manageable tasks.
  - Progress Tracking: The percentile completion allows you to gauge your overall progress at a glance.
  - Prioritization: Quickly identify and focus on tasks that need attention, ensuring efficient use of your time.
  - Flexibility: As you juggle multiple projects, adapt and prioritize tasks based on changing circumstances.
  - Journal Log: The journal can be used to keep track of each enclosure or habitat, take notes, or just write general reflections on the tasks regarding it in the journal.
- Potential Requirements:
  - Nested Scheduling: The ability to have different lists that can be easily differentiable from one another. Maybe being able to name certain lists
  - Task Percentage: Rather than fully checking off a task, provide a feature where they can check a certain amount of percentage and also be able to display the progress bar to the user.
  - Priority Setting: A feature to set the priority status of a task. This would allow people to set more important tasks to have a higher priority vs the lesser priority ones
  - Reminders: For really important or even just designated tasks there should be a way to have a reminder or a notification pop up to remind the user of that task
  - Easy UI: The user interface should be easy to use and easy to find the different lists without looking too cluttered.
  - Manageability: The user should be able to manage and change things such as priority status and other general things like the name of the task or where the task is.
![Pasted image 20240221075615](https://github.com/Sulavjung/Sulavjung-Documentation-for-Todo/assets/79497159/43635fc4-4820-493d-b77a-bf9a8fe75385)


### 9. A new dog owner wants to keep track of things to do for their dog.
- Actors: Dog owner, ToDoToday
- Assumptions:
  - Dog owner has access to internet
  - Dog owner has access to a device (phone or laptop)
- Use Case:
  A happy dog owner just got their first puppy and wants to provide the best care for it. Though, they feel a little overwhelmed with the new responsibilities that come with owning a pet. they decided to download ToDo Today to keep track of these new tasks. The dog owner starts listing each task needed to get done for their dog and starts prioritizing each task. The dog owner wants to prioritize training their dog as they think they should train a dog as soon as possible. The dog owner creates the main task “Teach puppy to sit” and creates subtasks such as: buy training treats, guiding puppy to sit down, and reward the puppy with treats when sitting. The dog owner utilizes giving weights to each subtask and wants to start the task. They decide to go to the pet store to buy treats. Once they finished buying the training treats, they mark it as complete and see that they are now 10% done with the main task. When the dog owner arrives home, they start training their puppy right away. They train their dog with positive reinforcement using treats every time the dog would sit down, marking the subtask complete and now at 40% total completion. The next couple of hours, the dog owner would be trying to train the dog to sit on command while still using positive reinforcement. The dog owner finally sees progress and has successfully trained their dog to sit on command. Feeling joyful, they mark the last subtask as complete, showing 100% completion. After using the app, the dog owner was pleased with the experience of a progress bar for their task.
- Benefits:
  - ToDoToday gave the dog owner a pleasant todo list experience with the progress bar
  - Able to assign weights to each subtask.
![Pasted image 20240221075639](https://github.com/Sulavjung/Sulavjung-Documentation-for-Todo/assets/79497159/7d9ac1ff-b728-4084-bc42-bb0b775f7064)


## IV. Main Data Items and Entities
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
   - **Meaning:** Groups tasks together under a common theme or goal. This could be something that is interchangeable to tasks. If the task itself has child task, it should be project.
   - **Usage:** Helps organize tasks and allows users to focus on specific objectives.
   - **Data Structure:** Consists of a name, description, and possibly a list of associated tasks.

### 4. Category:
   - **Meaning:** Classifies tasks into different types or categories. User is the one categorizing the tasks. 
   - **Usage:** Aids in organizing tasks based on their nature or purpose.
   - **Data Structure:** Contains a name and possibly a description.

![[Pasted image 20240215145021.png]]


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

***
## V. Initial List of Functional Requirements:

#### “Users shall be able to”
**User**
1. A user shall be able to register for a new account using a username, email, and password.
2. A user shall accept the terms and conditions before creating an account.
3. A user shall be able to log into their account using their email/username and password.
4. A user shall be able to nest subtasks inside of other subtasks.
5. A user shall be able to access the “app” only when they have an internet connection.
6. A user shall be able to mark a task done while being able to specify the percentage at which that task has been completed.
7. A user shall be required to give a valid email upon creating an account.
8. A user shall be able to edit tasks.
9. A user shall receive a notification for upcoming deadlines for tasks.
10. A user shall be able to add a new task, regardless if a previous task is incomplete.
11. A user shall be able to delete tasks.
12. A user shall be able to name and rename their new and existing tasks.
13. A user shall be able to add new subtasks even if the parent task is complete.
14. A user shall be able to review their previous journal entries.
15. A user shall be able to undelete a task.
16. A user shall be able to edit their profile information.
17. A user shall be able to update their email address.
18. A user shall be able to change their password.

**Task**
19. A task shall be able to be deleted and added.
20. A task shall be able to hold dates and times.
21. A task shall be able to hold certain priority flags depending on the importance.
22. A task shall be able to nest subtasks inside of other subtasks.
23. A task shall display the percentage completed.
24. A task shall display the overall percentage completion of its subtasks.
25. A task shall be raised up when given a high priority.
26. A task shall be pushed down when given a low priority.
27. A task shall warn the user if they reach the limit for subtasks.

**Journal**
28. A Journal shall generate a prompt for the user from their highest priority tasks.
29. A Journal shall give the user a new entry and prompt each day.
30. A Journal shall ask the user how they can improve.
31. A Journal shall remind them to reflect on their work.
32. A Journal shall be deleted when the user chooses to delete it.
33. A Journal shall be able to be undeleted within 12 hours of deletion.
34. A Journal shall prompt a user to delete old journals if there is not enough space.

**Calendar**
35. A calendar shall show the user’s upcoming deadlines.
36. A calendar shall notify the user of upcoming deadlines.
37. A calendar shall keep track of passed deadlines as well as upcoming deadlines.
38. A calendar shall be able to differentiate between todo lists.
39. A calendar shall have a week view.
40. A calendar shall have a month view.
41. A calendar shall be able to transition between those two views.

**Account**
42. An account shall be created by one user.
43. An account shall only be created by a user able to properly consent to our terms and conditions without the assistance of a parent or guardian.
44. An account shall be created with a username, email, and password.
45. An account shall be deleted upon the decision of the user.
46. An account shall be accessible across devices.
47. An account’s tasks shall be synchronized across devices.

**List**
48. A To-Do list shall be deleted when the user chooses to delete it.
49. A To-Do list shall, upon deletion, delete all tasks and subtasks beneath it.
50. A To-Do list shall be able to be differentiated from other To-Do lists.
51. A To-Do list shall be shareable.
52. A To-Do list shall be importable.

***
## VI. List of Non-Functional Requirements

**Usability:**
- The user interface should be intuitive and easy to navigate, with feedback loops as needed.
- Localization should be implemented to support users in different regions.
- Prompt generation is run by a GPT-2 API to ensure natural and contextually relevant prompts.

**Compatibility:**
- The Application should be iOS-compatible initially. If time allows, it should be optimized for Android and then web platforms as well.
- If optimized for all platforms, consistent behavior and UI clues should be maintained across different devices.
- Optimization should be done using native APIs as much as possible to ensure platform-specific performance and user experience.

**Performance:**
- The app should be able to handle a large number of tasks efficiently without significant performance degradation, ensuring smooth user experience even with heavy usage.

**Scalability:**
- The system should be scalable to accommodate an increasing number of users and tasks without compromising performance, ensuring reliability and responsiveness as the user base grows.

**Security:**
- Critical user information should be encrypted to protect user privacy and prevent unauthorized access.
- The app should be protected against security risks such as SQL injection and other common vulnerabilities to ensure data integrity and user safety.

**Code maintainability:**
- The codebase should be well-structured, modular, and thoroughly documented to facilitate ease of maintenance, updates, and future development efforts.

**Privacy:**
- User data should be handled securely, and where possible, encrypted to protect user privacy and confidentiality. Compliance with relevant privacy regulations should be ensured.
