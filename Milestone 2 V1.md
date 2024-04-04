<h1 style = "text-align: center"> SW Engineering CSC648-848-05 Spring 2024 </h1>
<p style = "text-align: center">Project Title: ToDo-Today</p>
<p style = "text-align: center">Team: 02 </p>
<p style = "text-align: center">Names of Group Members: </p> 

| Name             | Email                                                 | Role           |
| ---------------- | ----------------------------------------------------- | -------------- |
| Alex Nikols      | [anikols@mail.sfsu.edu](mailto:anikols@mail.sfsu.edu) | Team-Lead      |
| Jason Tran       |                                                       | Frontend-Lead  |
| Sulav Jung Hamal |                                                       | Backend-Lead   |
| Jadon Hoang      |                                                       | Github Master  |
| Randale Reyes    |                                                       | Database Admin |
| Christian Gopez  |                                                       | Docs-editor    |

<p style = "text-align: center">Milestone 2 </p>
<p style = "text-align: center">04/04/2024 </p>
<p style = "text-align: center">History Table </p>

| Date      | Revision                         |
| --------- | -------------------------------- |
| 4/4/2024  | Milestone 2 Revision 1           |
| 3/25/2024 | Final Milestone 1 Revision 2     |
| 3/1/2024  | Submitted Milestone 1 Revision 1 |


  ---
  ---
  
## Ⅰ. Brainstorming Ideas
### 1. Dungeon Finder:
An application similar to a dating app but for people, Dungeons and Dragons players. Using this app people who are looking for a group to play with would be able to connect with others. Users would be able to fill out a profile consisting of things such as the type of player they are, their character information, and also what they are looking for in a group.

**Pros:**

- An easy way for players to find a group
    
-   
    

**Cons:**
- ?
    
- ?  
      
    

### 2. ToDoToday (WIP):
   
A ToDo list that is able to support the ability to mark down a certain degree of percentage done for a task. The idea of not being able to mark down a task as done is demoralizing to the person and doesn't help in productivity. With this feature, we are able to make sure that we can keep track of and visualize the progress that we are making in the tasks that we mark down. There will also be a journal feature that can help the users to reflect and further digest how they are doing for a task.

**Pros:**

- Providing a motivating way for marking tasks off
    
- Journaling feature to help reflect on tasks
    

**Cons:**
- Many other competitors
    
- ?
    

### 3. RentABook:
Textbook rental service similar to that of Airbnb. We all have been in a position where either we do not have the funds to get a new textbook that is required for a class that we are taking or we bought a textbook and no longer have a use for it rendering it useless. This app fixes both of these problems because on this app you would be able to rent textbooks that you would need without having to pay the full price of that textbook. On the other hand, you would also be able to put the textbook that you have up for rent so that you can make money off of a book that you might not have a use for anymore. 

**Pros:**

- Can help provide texts and education for cheaper prices
    
- Can be another income source for those with old textbooks
    
**Cons:** 
- Legality?
    
- Would be hard to monitor and make sure the textbook owners do not get scammed
    

---
## Ⅱ. Executive Summary
TODo TODay is a To-Do List and daily task tracker app, with integrated calendar and journaling functions. What makes the TODo TODay app stand out are a couple of unique twists on the classic To Do List apps currently available on the market. The first of which is the ability to allow for partial completion of tasks and to mark them by percentage. This task system is also embedded into a nesting structure allowing for smaller tasks to be nested inside of larger tasks so you can understand your overall progress on projects or daily goals cleanly and intuitively. The other unique addition to this sort of To Do List app is a dynamic journaling function. This dynamic journal will use an AI GPT system to dynamically create new journal prompts for the user daily based on what is the highest priority on their current to-do list. 

TODo TODay is specifically designed to be an easy-to-use way of organizing anything from an individual's small tasks in their daily life to massive projects that may take months or years to complete. The reason why my team and I decided to create TODo TODay was to look into every other To Do List app and how they work. Every single application that we found was binary either the task was complete or it wasn't. This kind of binary choice can be very demoralizing for large projects and does not give you an overall understanding of your progress. We created this app to take the best parts of large project trackers that are used in the industry and bring them to a more public audience. As well as including tasks and tools to help users stay on track with their projects and make sure that they have enough time to get everything done.

TODo TODay‘s flexibility and structure help reinforce the habit of maintaining and updating their to-do list while also clearing off tasks from it. This positive reinforcement loop will not only help users be on top of all the regularly scheduled things they may need to do in their regular lives but also allow them to find time for themselves. The other thing TODo TODay will do is encourage the user to journal their experience and where they might be struggling with their tasks it will help them engage more fully in thinking about what they might be struggling with and how they might improve over time. Say somebody has practice guitar as a regular task they do weekly, then TODo TODay will bring that up in the journal and have the user talk about how they feel they are progressing in their guitar practice. When the user interacts and journal their experience it will help them crystallize and coalesce their feelings on how the practice has been going and how they have been doing which will help them better understand what they can do to keep improving and getting better at playing the guitar. This is just one example of the type of positive reinforcement and benefit you get out of the journaling and reevaluation process that TODo TODay is built around.

## Ⅲ. Main Use Case

### 1. Student managing their schedule 
    
- **Actor:** Student, TODOtoday Application
    
- **Assumptions:**
	- The student has access to the internet
	- The student has access to a device (desktop or laptop)

- **Use Case:**
This student is very busy, they are taking a heavy workload this semester and must have a way to organize and complete these tasks in a timely manner. Stressed out and anxious, the student decides to download an app, ToDoToday, which will be able to help organize and keep track of their classwork. In one of these courses, the student has been assigned a large project with multiple milestones and checkpoints. With the help of the ToDoToday app, the student assigns the whole project as the main task and milestones as a subtask to the main project. In addition to this, the student also adds the checkpoints as subtasks to the milestone subtasks. As the student completes the checkpoints, the progress bar for the milestone and the whole project increases. On top of this, they also use the calendar to keep track of what time their various assignments may be due and what's coming up next.  As a student works through his tasks and completes them they get marked as complete on the calendar. The student also got into the habit of using the journaling to reflect on how they did their assignments and where they can improve. With this in mind, the student feels much more at ease, feeling much less anxious about the project. Overall, the ability to observe the progression in the progress made on the project in its entirety induces a feeling of ease and relaxation. The newfound ability to journal these reflections also enforced what the student had learned from projects and assignments.

- **Benefits:**
	- Organization: The information and tasks are easily available for the student to see and manipulate
	    
	- Progress Tracking: The student can have a visual representation of tasks completed for the day and could have an idea of how much more is left to do.
	    

- **Potential Requirements:**
	- Nested Scheduling: The ability to have different lists that can be easily differentiable from one another. Maybe being able to name certain lists
	    
	- Task Percentage: Rather than fully checking off a task, provide a feature where they can check a certain amount of percentage and also be able to display the progress bar to the user. 
	    

![](https://lh7-us.googleusercontent.com/mCDOKSA4XxtxKXA-uhBwIJWv8_-ztpiscY92pb3X3rDhpSErF43y5j7xr2SsxddCwgL8FsplHfHUtPTcFZnnnLKfmyHfwFs6sukjGYs6-GTaqDBF8_KfCTU6xftu3Gpk6QBc4-2wBu2vlKLsmntYWDQ)

---
### 2. A mother trying to manage both their kid's differing schedule and varying tasks
- **Actor:** Parents, TODOtoday Application

- **Assumptions:**
	- Parents have access to the internet
	    
	- Parents have access to a device (desktop or laptop)
	    
- **Use Case:**
A mother is having a hard time trying to keep track of her children’s schedules throughout the school year due to them being in different extracurriculars. One of the kids is more athletic and is involved in more sports and physical activities. The other child is more into music and computers. The two children have varying schedules and the mother needs a way to schedule and organize them. This app will help keep the two schedules separate for easier viewing. Within these sub-lists, she will be able to list the different things she has lined up for the specific child. As she gets things done the progress percentage will reflect and show how many of the activities or tasks were completed for that child's schedule. There will also be a feature that the mother can use to mark certain tasks to be more important so that she would know which task she would have to focus on more at that time. Lastly, the journal feature will be able to give her time to reflect on the tasks done, what she could have done better, and overall reflect on her day.

- **Benefits:**
	- Organization: The information and tasks are easily available for the mother to see and manipulate
	    
	- Progress Tracking: The mother can have a visual representation of tasks completed for the day and could have an idea of how much more is left to do.
	    
	- Motivation: Rather than giving up, the journal will help with the ability to contemplate what she has done so far if things are a little overwhelming she be able to contemplate what to for next time.
	    

- **Potential Requirements:**
	- Nested Scheduling: The ability to have different lists that can be easily differentiable from one another. Maybe being able to name certain lists
	    
	- Task Percentage: Rather than fully checking off a task, provide a feature where they can check a certain amount of percentage and also be able to display the progress bar to the user. 
	    
	- Priority Setting: A feature to set the priority status of a task. This would allow people to set more important tasks to have a higher priority vs the lesser priority ones
	    

![](https://lh7-us.googleusercontent.com/5CnBhejefeR_eBUssohQxq4yzfGnb0TitSpyvSogLcf1YIqsjDbQ611o93XftdJlOicZDQB3z4jWpqKStvfkn0-_9a6kSk-tqdr_Iugofl4m_LbTUDA1dcCrGCVW1-pJ8Uxf2ke1Y1nbJRxAOqyAPio)

---
### 3. Patients utilizing the app to keep track and log their daily life

- **Actor:** Patients, Life Coach
    
- **Assumptions:**
	- Patients have access to the internet
	    
	- Patients have access to a device (desktop or laptop)
	    
- **Use Case:**
A life coach is helping patients day by day to help control and improve their patients lives. The life coach recommends the patient an app that would help them schedule their life schedules and tasks while also keeping track of their progress. The patient will be able to use the to-do list app to make lists of tasks needing their completion. They would also be able to set up subtasks to break down larger tasks to make them more manageable and less overwhelming.  They can use the calendar to not only keep track of scheduled appointments but also to manage their time throughout the week. They also would then be able to use the function of the journal app to keep tabs on how they are doing. The journal app will be a great feature for them as they would also be able to read and use the talking points they talked about in the journal section to their life coach and they would be able to debrief on the patient's week or day easier. With the addition of the progress bar the completion of tasks is no longer demoralizing but rather makes it motivating to get the percentage of the bar to 100.

- **Benefits:**
	- Self:Reflection: Through the journal app the patient will be able to keep track of not only themselves but also the tasks they need to do through the app
	    
	- Progress Tracking: The patient can have a visual representation of tasks completed for the day and could have an idea of how much more is left to do.
	    
	- Motivation: The visualization of the progress bar will be motivating to the patient to be able to get their tasks done. 
	    
- **Potential Requirements:**
	- Nested Scheduling: The ability to have different lists that can be easily differentiable from one another. Maybe being able to name certain lists
	    
	- Task Percentage: Rather than fully checking off a task, provide a feature where they can check a certain amount of percentage and also be able to display the progress bar to the user. 
	    
	- Priority Setting: A feature to set the priority status of a task. This would allow people to set more important tasks to have a higher priority vs the lesser priority ones
	    
	- Journal feature: This feature will help the user debrief and think about the tasks that they are doing. Essentially having a recap and potentially being able to think about what worked for them and what didn't. Could also have a part where they keep track of their results or progress on tasks. 
	    

![](https://lh7-us.googleusercontent.com/_Qu-g-Y8qUFiHTih3iziA0_g-ETfrqAiqWSyGOwdBlYV33pVfdu6ffkRj8G7DC6Kj1pnUJimPAQP8c_h6oEpu8sr7b4MTz9YQqNVsnq-4IFiBRa_nD9HckkX106K2PVhtKiJ14A61quMBRYwxOjgpU0)

---
### 4. Project Manager and Members using the app to organize tasks for the project

- **Actor:** Project Manager
    
- **Assumptions:**
	- The Project Manager has access to the internet
	    
	- The Project Manager has access to a device (desktop or laptop)
	    

- **Use Case:**
The project manager needs to lead multiple teams to develop a new software project. These teams need to work in harmony if they want to succeed in building this project. By using the ToDoToday app the teams working under the project manager would be able to keep track of their work and progress while working through the project. The teams will be able to mark the tasks while also keeping track of the dates so that they make sure they can make their due dates for certain tasks. This is also easily viewable in a calendar format so that they can visualize the task due dates better. This allows the product manager to manage each team in a much more efficient and organized manner. As each team completes its subtasks, the tasks check off what has been completed, gradually increasing the progress bar for the main project. Overall, the organization allows the project manager to keep up with deadlines and pinpoint which tasks teams need to focus on to work in unison.

- **Benefits:**
	- Organization: The Employees or project members can make different lists for their tasks which could also have subtasks to break down the tasks even more. 
	    
	- Task Percentage: The Task Percentage will be helpful in that there is a visualization of how much the task has been done. 
	    
	- Priority Setting: Being able to choose which things are more urgent than others will be of help wot make sure that the things that need to be done are done before moving on in their project.
	    
- **Potential Requirements:**
	- Nested Scheduling: The ability to have different lists that can be easily differentiable from one another. Maybe being able to name certain lists
	    
	- Task Percentage: Rather than fully checking off a task, provide a feature where they can check a certain amount of percentage and also be able to display the progress bar to the user. 
	    
	- Priority Setting: A feature to set the priority status of a task. This would allow people to set more important tasks to have a higher priority vs the lesser priority ones
	    

![](https://lh7-us.googleusercontent.com/BOvU_MVb1j_j-JpIryEJdjGygSVJn5olfRCDwws_GORTyMTaOVq9dWGxZu7MKO_lQFgcf_2kkZ9e0GFr5CjyMiAdI21sKLec40GTq-FTzkOObb0k8HA6YHp332uiqJNRZtsJL8SHrq-YwxPWJna4WtU)

### 5. Teachers using the app to plan their lessons for the different subjects that they are teaching

- **Actor:** Teacher
    
- **Assumptions:**
	- The Teacher has access to the internet
	    
	- The Teacher has access to a device (desktop or laptop)
	    
- **Use Case:**
The teacher is planning on teaching multiple sections of courses varying in different subjects. With the app, they would be able to list out specific tasks and lists for that specific class. Keeping the different to-do lists organized and sectioned for readability. They would be able to make different sub-lists pertaining to subjects such as math, science, and history. They would be able to have the lesson plan and then another list under that for checking off the material and steps on that lesson plan. Then depending on how the different subjects went the teacher would be able to log the lesson and talk about the things that she liked or things that she could improve on using the journal function of the app. If there is an important thing that is going on in a specific class such as one of them having a quiz or a test on a certain day, they would be able to mark that quiz or test as a high priority so that it is not missed. Using the calendar the teacher will be able to keep track of when quizzes, exams, and other class milestones are approaching to make sure that she is keeping up with the schedule that she has laid out for the class.

- **Benefits:**
	- Organization: The Teacher can have separate lists for their needs. Through this, they have multiple to-do lists that they can easily access and find
	    
	- Task Percentage: The Task Percentage will be helpful in that there is a visualization of how much the task has been done. They would also be able to see how much of the lesson plan they did by looking at the percentage of that task’s bar. 
	    
	- Priority Setting: Being able to choose which things are more urgent than others will be of help to make sure that important things are not forgotten. 
	    
- **Potential Requirements:**
	- Nested Scheduling: The ability to have different lists that can be easily differentiable from one another. Maybe being able to name certain lists
	    
	- Task Percentage: Rather than fully checking off a task, provide a feature where they can check a certain amount of percentage and also be able to display the progress bar to the user. 
	    
	- Priority Setting: A feature to set the priority status of a task. This would allow people to set more important tasks to have a higher priority vs the lesser priority ones
	    
	- Easy UI: The user interface should be easy to use and easy to find the different lists without looking too cluttered.
	    

![](https://lh7-us.googleusercontent.com/wMziHyIDx9V_lDpSBxl60dijbDyXJ1Pi7y-juLTG2x1_xgxsmzlh1FHSFN0qbwFWUfmktmj_mhm56L1DoUs5SYq6UpcRTDJF5fkitVdFqupeUA0pgWSvBHfBYqEEw0rMPMP1C6hzfUeXZ6V1Bv764iM)

---
### 6. A Traveler planning their trip and preparations

- **Actor:** Traveler
    
- **Assumptions:**
	- The traveler has access to the internet
	    
	- The traveler has access to a device (desktop or laptop)
	    
- **Use Case:**
Sarah is planning a vacation to Europe. She uses the app to create a packing list with items such as clothes, toiletries, and travel documents. As she packs each item,  she checks it off in the app. She could see the completion rate of each place and uniquely identify which place she still needed to visit. As for the rip itself, she can make a subtask that can take care of activities and things that she wants to do on the trip. She can also assign dates to these tasks and will be able to view them on the calendar for ease of view. This gives her a way to have an overview of the trip and what she can expect on certain days. As she checks off the activities it also gives her an indication of how much is left in the trip that she has planned. This can help her in many ways one being that if the progress bar is almost full but she has more time wherever she is staying this tells her that there is more room for other activities and she can plan accordingly. 

- **Benefits:**
	- Organization: It is easy for Sarah to make a list to track things such as things to pack. She can make lists of any of her needs during the trip through the app
	    
	- Tracking: The lists that she makes can display the progress that she has made so that she can visually see how much else she has to pack, or how many more things she has to do in a certain city.
	    
	- Planning: The app will make her planning easier and more accessible through the ability to create, change, and manage the different lists available through the app. 
	    
- **Potential Requirements:**
	- Nested Scheduling: The ability to have different lists that can be easily differentiable from one another. Maybe being able to name certain lists
	    
	- Task Percentage: Rather than fully checking off a task, provide a feature where they can check a certain amount of percentage and also be able to display the progress bar to the user. 
	    
	- Priority Setting: A feature to set the priority status of a task. This would allow people to set more important tasks to have a higher priority vs the lesser priority ones
	    
	- Easy UI: The user interface should be easy to use and easy to find the different lists without looking too cluttered.
	    
	- Manageability: The user should be able to manage and change things such as priority status and other general things like the name of the task or where the task is.
	    
![](https://lh7-us.googleusercontent.com/0CTKMZ1aovV5uWkXZCEN2--IXu43f1Sjg43Aiu6LsMmXmH0oIjv_cW2oaYEI0NVlGu5ndeWFg5fSwAvAnJdd5_VL5YpUnH5-EmlSmqSZe9FwGMTN4kSXT3Wpw8WYEV_tj8yGHJaEfJkiS3zZSiy3i3U)

---
### 7. Hobbyist working on multiple small side projects/models.
- **Actor:** Hobbyist 
    
- **Assumptions:** 
	- The hobbyist has an Internet connection 
	    
	- The hobbyist has access to a device (desktop or laptop)
	    
- **Use Case:**
This hobbyist is attempting to build a bookshelf in their workshop. They heard about a to-do list app from one of their friends for managing projects. He decides to check out a to-do list web app, (ToDo ToDay). He then makes a new to-do list using the app to organize his bookshelf-building project. He then set up the main task for that to-do list first being researching the type of bookshelf he wants to build. Then he creates his first task, research. Next, he creates subtasks for researching styles of bookshelves, researching materials, and researching the hardware he is going to use. He quickly decides to use the hardware he has on hand and gets that first subtask done then he moves on to research materials. He finds a deal on walnut wood and decides that that will be the material he’ll use for the project. Moving over to one of the other tasks, the purchase of materials, he goes down to purchase, the wood for the body section and marks it off. He continues down the to-do list marking off tasks, building and setting everything up until he has everything ready for the bookshelf. He starts building the outside frame first and gets that done the first day. He marks that off his list and sees that he only has the shelves and the backside of the shelf to do next so he’s already 68% of the way through his project. Feeling more confident he continues to build the body of the bookshelf and now he is closer to 85% completion, all that’s left is finishing that up and then doing the final stages of staining and putting in hardware can check off everything from the list and it shows his completion at 100%. Once he is finished he then uses the Journal to reflect on what he struggled with and how he can improve for his next project.

- Benefits:
	- Organization: Easily break down your projects into smaller, manageable tasks.
	    
	- Progress Tracking: The percentile completion allows you to gauge your overall progress at a glance.
	    
	- Prioritization: Quickly identify and focus on tasks that need attention, ensuring efficient use of your time. 
	    
	- Flexibility: As you juggle multiple projects, adapt and prioritize tasks based on changing circumstances. 
	    
	- Motivation: Seeing progress percentages can be motivating and help you stay on track with your hobby projects
	    
- **Potential requirements:**
	- Nested Task Management: The app should support the creation of hierarchical task structures, allowing users to break down larger projects into smaller, more manageable subtasks. 
	    
	- Task Percentage Completion: The app needs to have a feature that allows users to assign and visualize completion percentages for each task, providing a quick overview of the overall progress. 
	    
	- Prioritization: There should be functionality for users to prioritize tasks within a project, helping them focus on what needs immediate attention. 
	    
	- Flexibility and Adaptability: The app should allow users to easily modify and rearrange tasks as project requirements change or evolve over time. 
	    
	- Multi-Project Support: Since the hobbyist is working on multiple small projects simultaneously, the app should enable users to organize and switch between different projects efficiently.
	    
	- User-Friendly Interface: The app should provide an intuitive and user-friendly interface to enhance the overall user experience, making it easy for the hobbyist to manage tasks without a steep learning curve.
	    
	- Motivational Features: Including visual elements or notifications that celebrate task completion milestones could contribute to a more motivating user experience.
	    

![](https://lh7-us.googleusercontent.com/1I2-FvFgtRIRpNrQDqP1ACfA52RdC1CipeAkucc4q_zXaK_NUkZ34GjF_3BM4fkPpyJKpbJGx5GG9qPnVQYnihQFWQUq7uAIbZZ49w29itw0eCyASl9tDW6YuDr1gs4HsMf3ys4HZo7THK0gPjji0vI)

---
### 8. A zoo keeper keeps an eye on and maintains different species of animals in the zoo using the app to keep track of each enclosure. 

- **Actor:** Zoo-Keeper
    
- **Assumptions:**
	- The Zoo-Keeper has access to the internet
	    
	- The Zoo-Keeper has access to a device (desktop or laptop)
	    
- **Use Case:**
Zookeeper was overwhelmed when trying to care for and keep track of the dietary and other needs of all of the different animals that were under his care. He found an app called To Do Today, that allowed him to set tasks for each animal that he had to take care of, and under that task, it set subtasks for their dietary requirements and any other task that he might need to do for each individual animal. This app was very convenient for him because it allowed him to not only keep track of feeding schedules using their calendar but also the percentage of completion of taking care of each animal during his shift. He uses the journaling function to keep track of the animal's preferences for what they eat and other quirks. His Journal becomes a record of how to handle each animal.  With the app, he's found his job significantly more enjoyable and a lot less stressful as he does not have to worry about getting confused and either doing tasks twice or missing tasks.

- **Benefits:**
	- Organization: Easily break down your projects into smaller, manageable tasks.
	    
	- Progress Tracking: The percentile completion allows you to gauge your overall progress at a glance.
	    
	- Prioritization: Quickly identify and focus on tasks that need attention, ensuring efficient use of your time. 
	    
	- Flexibility: As you juggle multiple projects, adapt and prioritize tasks based on changing circumstances. 
	    
	- Journal Log: The journal can be used to keep track of each enclosure or habitat, take notes, or just write general reflections on the tasks regarding it in the journal.
	    
- **Potential Requirements:**
	- Nested Scheduling: The ability to have different lists that can be easily differentiable from one another. Maybe being able to name certain lists
	    
	- Task Percentage: Rather than fully checking off a task, provide a feature where they can check a certain amount of percentage and also be able to display the progress bar to the user. 
	    
	- Priority Setting: A feature to set the priority status of a task. This would allow people to set more important tasks to have a higher priority vs the lesser priority ones
	    
	- Easy UI: The user interface should be easy to use and easy to find the different lists without looking too cluttered.
	    
	- Manageability: The user should be able to manage and change things such as priority status and other general things like the name of the task or where the task is.
	    

![](https://lh7-us.googleusercontent.com/9yoi-E9c9cnOTO73l-ZOS1-k4xpPOQDY8GWZswyh9dnaDr4mXWgx4OqC25hwmNPJl1F69CoVgbIctSrbhhbCo32YWG0onqBbcsOo5GFMk6845gNTCsMABRAEU2L5rJRz8FS6xoLYGd38l3Ny5ARCJBY)

---
### 9. A new dog owner wants to keep track of things to do for their dog.

- **Actors:** Dog owner, ToDoToday
    
- **Assumptions:**
	- The dog owner has access to the internet
	    
	- The dog owner has access to a device (desktop or laptop)
	    
- **Use Case:**
A happy dog owner just got their first puppy and wants to provide the best care for it. However, they feel a little overwhelmed with the new responsibilities of owning a pet. they decided to download ToDo Today to keep track of these new tasks. The dog owner starts listing each task needed to get done for their dog and starts prioritizing each task. The dog owner wants to prioritize training their dog as they think they should train a dog as soon as possible. The dog owner creates the main task “Teach the puppy to sit” and creates subtasks such as: buying training treats, guiding the puppy to sit down, and rewarding the puppy with treats when sitting. The dog owner utilizes giving weights to each subtask and wants to start the task. They decide to go to the pet store to buy treats. Once they finished buying the training treats, they marked it as complete and saw that they were now 10% done with the main task. When the dog owner arrives home, they start training their puppy right away. They train their dog with positive reinforcement using treats every time the dog sits down, marking the subtask complete and now at 40% total completion. For the next couple of hours, the dog owner would be trying to train the dog to sit on command while still using positive reinforcement. The dog owner finally sees progress and has successfully trained their dog to sit on command. Feeling joyful, they mark the last subtask as complete, showing 100% completion. After using the app, the dog owner was pleased with the experience of a progress bar for their task. 

- **Benefits:**
	- ToDoToday gave the dog owner a pleasant todo list experience with the progress bar
    
	- Able to assign weights to each subtask
    
	- The weights and priorities can determine which tasks are more important for the dog at that time
    
	- Subtasks for bigger tasks such as training for a trick. The dog owner would be able to break that process down into different tasks
    
	- Progress is shown through the bar visualization showing the dog's progress in learning tricks  
- **Potential Requirements:**
	- Nested Scheduling: The ability to have different lists that can be easily differentiable from one another. Maybe being able to name certain lists
    
	- Task Percentage: Rather than fully checking off a task, provide a feature where they can check a certain amount of percentage and also be able to display the progress bar to the user. 
    
	- Priority Setting: A feature to set the priority status of a task. This would allow people to set more important tasks to have a higher priority vs the lesser priority ones
    
	- Easy UI: The user interface should be easy to use and easy to find the different lists without looking too cluttered.
    
	- Manageability: The user should be able to manage and change things such as priority status and other general things like the name of the task or where the task is.

![](https://lh7-us.googleusercontent.com/rUx7AAzWBIys_ue1OUnKAINjkuYt0HWv_jNELu7Rds9R6GDLPHBJcoW6ogH6oER3hGFBk8CSIXUaaZJBgRpTWDft8maWed0_1dgXVGdzX7XepkKk-KyZcqgjiZBlecM0KMnPjEMCqu5HDRQ48Gla9hE)

---
## Ⅳ. Main Data Items and Entities
Here are some of the main data items and entities.

### 1. Task:
- **Meaning:** Since it is a to-do app, it should have at least a task. It represents an activity or item that needs to be completed.
    
- **Usage:** Users can create, view, edit, and delete tasks within the application.
    
- **Data Structure:** Contains fields such as task ID, description, due date, priority, status, associated user ID, and many more.  
      

### 2. User:
- **Meaning:** Users are anyone who will be using the application.
    
- **Usage:** Users can register, log in, and manage their tasks.
    
- **Data Structure:** Includes fields like username, email, password, and possibly additional profile information.  

### 3. Project:
- **Meaning:** Groups tasks together under a common theme or goal. This could be something that is interchangeable with tasks. If the task itself has a child task, it should be a project.
    
- **Usage:** Helps organize tasks and allows users to focus on specific objectives.
    
- **Data Structure:** Consists of a name, description, and possibly a list of associated tasks.  

### 4. Category:

- **Meaning:** Classifies tasks into different types or categories. The user is the one categorizing the tasks.
    
- **Usage:** Aids in organizing tasks based on their nature or purpose.
    
- **Data Structure:** Contains a name and possibly a description.

![](https://lh7-us.googleusercontent.com/m8vbbms7PSS5U6GKl_H3fPqpuZV3FW_x0VG0pB6SnKYhyAV3F69rMCQIAxYvxUZlCF4N2syfXIhe3eyVY8I3mkvUJBe2u5LfNSaLit-1YQONBcpSSDe0FlXRxtUYy-hYbQEwU2btEFasz3fTbe3ZHMU)

**Few More:**
There are not-so-important items that in themselves aren't data items but do consist of categorical data.
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
    
---

## Ⅴ. Initial List of Functional Requirements

**Functional Requirements:**
“Users shall be able to”

**User**

1. A user shall be able to register for a new account using a username.
    
2. A user shall be able to register for a new account using an email.
    
3. A user shall be able to register for a new account using a password. 
    
4. A user shall accept the terms and conditions before creating an account.
    
5. A user shall be able to log into their account using their email/username and password. 
    
6. A user shall be able to nest subtasks inside of other subtasks. 
    
7. A user shall be able to access the “app” only when they have an internet connection.
    
8. A user shall be able to mark a task done while being able to specify the percentage at which that task has been completed.
    
9. A user shall be required to give a valid email upon creating an account.
    
10. A user shall be able to edit tasks
    
11. A user shall receive a notification for upcoming deadlines for tasks. 
    
12. A user shall be able to add a new task, regardless if a previous task is incomplete.
    
13. A user shall be able to delete tasks
    
14. A user shall be able to name and rename their new and existing tasks.
    
15. A user shall be able to add new subtasks even if the parent task is complete.
    
16. A user shall be able to review their previous journal entries.
    
17. A user shall be able to undelete a task 
    
18. A user shall be able to edit their profile information
    
19. A user shall be able to update their email address
    
20. A user shall be able to change their password
    

**Task**

21.  A task shall be able to be deleted and added
    
22.  A task shall be able to hold dates and times
    
23.  A task shall be able to hold certain priority flags depending on the importance
    
24.  A task shall be able to nest subtasks inside of other subtasks. 
    
25.  A task shall display the percentage completed
    
26.  A task shall display the overall percentage completion of its subtasks 
    
27.  A task shall be raised up when given a high priority 
    
28.  A task shall be pushed down when given a low priority 
    
29. A task shall warn the user if they reach the limit for subtasks
    

**Journal**  

30.  A Journal shall generate a prompt for the user from their highest-priority tasks
    
31.  A Journal shall give the user a new entry and prompt each day.
    
32.  A Journal shall ask the user how they can improve.
    
33.  A Journal shall remind them to reflect on their work.
    
34.  A Journal shall be deleted when the user chooses to delete it
    
35.  A Journal shall be able to be undeleted within 12 hours of deletion
    
36.  A Journal shall prompt a user to delete old journals if there is not enough space
    

**Calendar**

37.  A calendar shall show the user’s upcoming deadlines
    
38.  A calendar shall notify the user of upcoming deadlines
    
39.  A calendar shall keep track of passed deadlines as well as upcoming deadlines
    
40.  A calendar shall be able to differentiate between todo lists 
    
41.  A calendar shall have a week view
    
42.  A calendar shall have a month view
    
43.  A calendar shall be able to transition between those two views.
    

**Account**

44.  An account shall be created by one user
    
45.  An account shall only be created by a user able to properly consent to our terms and conditions without the assistance of a parent or guardian
    
46.  An account shall be created with a username.
    
47.  An account shall be created with an email.
    
48. An account shall be created with a password.
    
49.  An account shall be deleted upon the decision of the user
    
50.  An account shall be accessible across devices (Desktop/Laptop)
    
51.  An account’s tasks shall be synchronized across devices (Desktop/Laptop)
    

**List**

52.  A To Do list shall be able to delete tasks when the user chooses to delete it 
    
53.  A To Do list shall upon deletion delete all tasks and subtasks beneath it.
    
54.  A To Do list shall be able to be differentiated from other To Do lists
    
55.  A To Do list shall be shareable
    
56.  A To Do list shall be importable
    

---
## Ⅵ. List of Non-Functional Requirements

### Non-functional requirements:

**Usability:**
- The user interface should be intuitive and easy to navigate, with feedback loop as needed.
    
- Prompt generation is run by a GPT2 API.
    

**Compatibility:**
- The Application should be compatible Firefox version 123
    
- If optimized for a desktop webpage environment, the consistent behavior and UI clues should be maintained.
    
- Optimization should be done with the use of native API's as much as possible.
    

**Performance:**
- The app should be able to run on a virtual system with 1 VCPU 1 GiB RAM efficiently without significant performance degradation.
    

**Scalability:**
- The system should be scalable to accommodate an increasing number of users and tasks without compromising performance.
    
**Security:**
- Critical user information should be encrypted.
    
- The app should be protected against security risks such as SQL injection.
    

**Code maintainability:**
- The codebase should be well-structured, modular, and thoroughly documented.
    

**Privacy:**
- User data should be handled securely and if possible, encrypted.  
      

---
## Ⅶ. Competitive Analysis
- **Competitive Analysis Table #1**
    
![](https://lh7-us.googleusercontent.com/nS6w7PWt0prutpdz84xPsdI0v3IgRW4iHp0VJ42MPfUBFK69vVOI2pgASywITZa-Gdbf_yHH9QAOiE5pFvNUgxKWZE4dpMEZ7VT7U9LMFD7gf7-DNNSqGAgNBRPmxOIY7ViIelOVlL9cSWdRHee2tTw)


- **Competitive Analysis Table #2**

| Feature          | Minimalist | Toodledo | Microsoft To Do | TeuxDuex | AnyDo | TickTick | Our Product |
| ---------------- | ---------- | -------- | --------------- | -------- | ----- | -------- | ----------- |
| Priority Setting | -          | +        | +               | -        | +     | +        | +           |
| Calendar Viewing | -          | -        | +               | +        | +     | +        | +           |
| Widgets          | -          | -        | -               | -        | +     | ++       | -           |
| Progress Bar     | -          | -        | -               | -        | -     | -        | ++          |
| Journal Feature  | -          | -        | -               | -        | -     | -        | ++          |
| Multiple Lists   | +          | +        | +               | +        | +     | +        | +           |
| Different Styles | +          | +        | +               | -        | +     | +        | -           |
| SubTasking       | +          | -        | -               | -        | -     | -        | ++          |
  
### 1. Minimalist: 
In minimalist using the app can be a little frustrating at times since it is designed to be as minimal as possible. The design has certain tasks and operations that are not bound to a specific key press or normal action, instead, they are bound to swipes taps, and shakes of your device. The visual layout is relatively clean clutter-free and pleasant to look at but sacrifices its usability in its pursuit of the absolute minimalist To Do List app. It allows you to create multiple folders and multiple to-do lists but this is only unlocked after you've created the 1st To Do List. The undo and delete functions are tied to the gyroscope of your phone you shake to delete. Which I feel is a little dangerous just in case you accidentally drop your phone or it misreads the vibrations of a particularly rough ride as you saying you want to delete A to-do list. One thing that the app does well though is that it allows you to have one main List task and then a couple of sub-tasks underneath it but it will only let you do one layer deep it will not let you do multiple sub-layers of subtasks nesting into each other.

### 2. Toodledo:
In Toodledo, adding a task is relatively simple as well as searching for a task, these features are at the top of the page and hard to miss. Creating side notes for a task is something Toodledo gives its users to add more context and clarification to a task. Toodledo also displays its task attributes on the main page such as task name, the folder the task is in, task start date, task due date, how frequently the task should be repeated, and task priority ranging from -1 to 3.

### 3. Microsoft To Do:
Microsoft to do software is solid and simple and a good baseline for what A to do list software should be. It has a simple and intuitive interface but little to no onboarding steps you literally open it up and it says welcome to Microsoft to do and that's about it there's no tutorial there's no walkthrough for how to access and how to set up your to do lists you have to figure it out yourself. One of the key things that makes Microsoft to do stands out from other To Do List applications is its integration into the Microsoft ecosystem. Since it is a first party product it has direct connections to outlook to other office suite products and allows for much more direct connections between them. As long as you have an Office 365 account you can use Microsoft to do for free. As it is sort of an add-on it's hard to define its price as an individual package.

### 4. TeuxDuex:
TeuxDeux is a straightforward to-do app that helps you stay organized, whether you're on your computer or on the go with your phone. Its simplicity makes it easy to use, and since it's cloud-based, you can access your tasks from anywhere and keep them synced across all your devices. So, my experience with this application was very smooth but I kept missing some of the major feature that I was used to with other applications. For instance, you can't set specific times for tasks or add detailed descriptions. Reminders, sub-tasks, and the option for partial completion are also missing. While the mobile version is free, the web version offers additional features for $4 per month or $36 per year. That felt backward or opposite to me as that didn’t make any sense. Despite not being very active on social media, TeuxDeux offers a hassle-free sign-up process and a generous 30-day free trial for the web version, making it easy for new users to give it a try and see if it suits their needs.

### 5. AnyDo:
The onboarding process was extremely quick. After giving it an email, your name, and making a password, it first asks if you’re planning to use it just for yourself, or with a team. I chose the option called “Just me” and it prompted me to add my first tasks. At most, it’s three tasks, but one task is enough to proceed. It briefly shows if I already want to make a subscription to upgrade to Premium by showing me the different prices, but I skipped it. After that, that was it, I already made multiple tasks, scheduled them on different times and days, and imported my calendar. However, I spent more time being lost and finding things out than it took for me to get started. It lets me import my calendar that’s integrated with my phone, so now it shows me what’s already on my calendar, but doesn’t notify me of anything from it. It also has the option to use AI to “Suggest a task for me”, which I’m not sure exactly what that would be like. It’s a Premium function, so I haven’t been able to test it. As of now, I haven’t paid for anything, and I’m not sure I will in the future.

### 6. TickTick:
TickTick allows the user to make different lists for their differing needs. Making the tasks for the list is very simple and intuitive. You can set different priorities for the tasks depending on how urgent the task is. There is also a feature where you can view the tasks in a calendar view which makes it easy to view to the user. Other features include things such as a habit tracker and even a tool for using the Pomodoro technique to boost focus. The app also allows for many different customization features in the app regarding how the app looks visually through different themes. 


**Planned Advantages:** 
From our competitive analysis our application stands out in three key ways the first of which being the progress bar which allows for a more granular understanding of where you're at in a current project and how close you are to being finished. The next is our AI powered journaling feature which uses a GPT 2 open source API to generate journaling prompts to keep you on task and keep you thinking about what your next steps should be for your project. Finally there was only one other application that allowed you to create subtasks, that was minima list, and that application would only let you create a single layer of subtasks. Our apps implementation of subtasks will be more flexible as it going to use a recursive structure allowing for a sub task to have a subtask of its own and so on and so forth down to the granularity that you may need. Overall our app stands out on those three key metrics allowing us to Stand out in an already crowded market.

**Additional Graphs:** 

![](https://lh7-us.googleusercontent.com/45EESZ6LX70K6OS7GDUymwdqi0b_QIa32DydyoQb3wYu67B-9kvHf1kn0pmx83PnJnvJSED7xNUVuAPXkH0IYUUOJXHp7lZWPkVT5K-YtBQyuq4Z2qZB5-2m5-djqEW2Bx1lAGN_Twd0k6ygpr8EFFY) 

---
## IX. Checklist

| Task                                                                                                                                   | Status |
| -------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| Team found a time slot to meet outside of the class                                                                                    | Done   |
| GitHub master chosen                                                                                                                   | Done   |
| Team decided and agreed together on using the listed SW tools and deployment server                                                    | Done   |
| Team ready and able to use the chosen back and front-end frameworks and those who need to learn are working on learning and practicing | Done   |
| Team lead ensured that all team members read the final M1 and agree/understand it before submission                                    | Done   |
| Github is organized as discussed in class (e.g. master branch, development branch, a folder for milestone documents, etc.)             | Done   |


---
## X. High-level Architecture

1. **Software stack:**
    
2. **Sever Host:** Amazon AWS EC2 1VCPU 1 GiB RAM
    
3. **Operating System:** Ubuntu Server 22.04 LTS
    
4. **Database:** MySQL Community Server 8.0.33
    
5. **Web Server:** Node.js 20.11.1 and Express.js 4.18.2
    
6. **Server-Side Language:** JavaScript
    
7. **Additional Technologies:**
	- **Web Framework:** React
	    
	- **IDE:** VSCode, Webstorm
	    
	- **APIs:** Huggingface GPT2 API
	    
	- **Packet manager:** NPM
	    
	- **Password encryption**: bcrypt 5.1.1
	    

---
  
## XI. List of team contributions (Milestone 1):

| Name             | Code | Documentation |
| ---------------- | ---- | ------------- |
| Alex Nikols      | 2    | 7             |
| Jason Tran       | 2    | 5             |
| Sulav Jung Hamal | 10   | 9             |
| Jadon Hoang      | 2    | 6             |
| Randale Reyes    | 2    | 5             |
| Christian Gopez  | 2    | 7             |

---

## ⅩⅡ. Data Definitions
- **ToDoToday:** The application name.
    
- **Dashboard:** 
	- The main page of the application where the tasks are displayed.
	    
- **Calendar:** 
	- The calendar allows for tasks to be displayed on the dates they are assigned.
	    
- **Journal:** 
	- The journal is where the user would be able to write down their journal entries and view past entries.
	    
- **Prompt:** 
	- A prompt will be provided to the user for the journal entry.
	    
- **Journal Entries:** 
	- Journal entries would hold the input the user enters for the journal.
	    
- **ToDo List:** 
	- The ToDo List is what will be holding all the tasks that the user creates.
	    
- **TodoItem:**
	- the TodoItem class represents individual tasks with various attributes such as priority, status, and due date.
	    
- **Main Task:** 
	- A Main Task would be a task that can hold subtasks or also be independent itself.
	    
- **Sub Task:** 
	- A Sub Task would be tasked under the main task usually splitting the main task into separate parts.
	    
- **Priorities:** 
	- Priorities are used to differentiate the importance of the different tasks
		- High: Very Important 
		    
		- Medium: Important
		    
		- Low: Not as Important as of now
		    
- **Progression Percentage:** 
	- This would be used to name the progression bar that we plan to implement. The progression percentage will show the progress that the user has on certain tasks visually through a progression bar. 
	    
- **Due Date**
    
- **Log In**
    
- **Log Out**
    
- **Register**
    
- **Username**
    
- **Email**
    
- **Password**
    
- **Account**
    
- **Settings**
    
---
## ⅩⅢ. Prioritized Functional Requirements
### Priority 1: 

**User:**

1. A user shall be able to register for a new account using a username.

2. A user shall be able to register for a new account using a valid email.

3. A user shall be able to register for a new account using a password.

4. A user shall be able to accept the terms and conditions.

5. A user shall be able to log into their account using their email.

6. A user shall be able to log into their account using their username.

7. A user shall be able to log into their account using their password.

8. A user shall be able to change their password.

**Task:**

9. A task shall be able to be deleted.

10. A task shall be able to be added.

11. A task shall display the percentage completed.

12. A task shall display the overall percentage completion of its subtasks.

13. A task shall be able to nest subtasks inside of other subtasks.

14. A task shall display the progress of a task using a progress bar.

15. A task shall update depending on the subtask's progress.

**Journal:**

16. A Journal shall generate a prompt for the user based on their higher-priority tasks.

17. A Journal shall have an input section for user reflections.

18. A journal shall be accessible by an account.

19. A Journal shall contain a prompt generated from the user's top 5 priority tasks.

**Calendar:**

20. A calendar shall have a monthly view.

21. A calendar shall present the title of the task on the task's due date.

22. A calendar shall have the due date of the task on the day the task is due.

**Account:**

23. An account shall be created by one user.

24. An account shall only be created by a user able to properly consent to our terms and conditions without the assistance of a parent or guardian.

25. An account shall be created with a username.

26. An account shall be created with an email.

27. An account shall be created with a password.

28. An account shall be created with a confirmed password.

29. An account shall be able to access the “app” only when they have an internet connection.

30. An account shall be able to mark tasks as done.

31. An account shall be able to delete tasks.

32. An account shall be able to name new tasks.

33. An account shall be able to rename existing tasks.

34. An account shall be able to add a new task, regardless if a previous task is incomplete.

35. An account shall have multiple journal entries.

36. An account shall display the account username.

**ToDo List:**

37. A ToDo list shall be searchable by the user.

38. A ToDo list shall delete all subtasks beneath it upon deletion of a task.

39. A ToDo list shall upon deletion of a to-do list delete all tasks inside that list.

**Settings:**

40. A setting shall allow the user to change their username.

41. A setting shall allow the user to change their email.

42. A setting shall allow the user to change their password.

**Dashboard:**

43. A dashboard shall allow the user to see an overview of their tasks.

44. A dashboard shall allow the user to see an overview of their upcoming tasks.

---
### Priority 2: 

**User:**

1. A user shall be able to edit their profile information.

2. A user shall be able to update their email address.

**Task:**

3. A task shall be able to hold dates and times.

4. A task shall be able to hold certain priority flags depending on the importance as high, medium, or low.

5. A task shall be raised up when given a high priority.

6. A task’s deadline shall be able to be shown in the calendar.

**Journal:**

7. A Journal shall ask the user how they can improve.

8. A Journal shall remind them to reflect on their work.

9. A Journal shall be deleted when the user chooses to delete it.

10. A journal shall have a collection of previous journal entries from the user.

11. A journal shall have a prompt of less than 150 words.

12. A journal shall have an open-ended prompt.

13. A journal shall have a date created.

**Calendar:**

14. A calendar shall show the user’s upcoming deadlines.

15. A calendar shall keep track of passed deadlines as well as upcoming deadlines.

16. A calendar shall present the time the task is due on the day of the task's due date.

17. A calendar shall present the priority of the task on the day of the task's due date.

18. A calendar shall have color-coded tasks.

**Account:**

19. An account shall be deleted upon the decision of the user.

20. An account shall be able to review their previous journal entries.

21. An account shall be able to specify completion via percentage.

22. An account shall be able to sort through all their tasks by priority.

23. An account shall be able to search through all their subtasks and main tasks.

24. An account shall have a profile icon.

25. An account shall allow the user to edit profile information.

26. An account shall display the account icon.

27. An account shall have a delete profile option.

**ToDo List:**

28. A ToDo list shall be able to delete a task when the user chooses to delete it.

29. A ToDo list shall be able to be renamed by the user.

30. A ToDo list shall be named by the user upon creation.

31. A ToDo list shall have a name to differentiate it from other To Do lists.

**Dashboard:**

32. A dashboard shall allow the user to see an overview of their overdue tasks.

33. A dashboard shall allow the user to mark completed quickly and easily.

---
### Priority 3: 

**Task:**

1. A task shall be pushed down when given a low priority.

2. A task shall warn the user if they reach the limit for subtasks.

3. A task shall have a category listed.

4. A task shall be able to be color-coded.

**Journal:**

5. A Journal shall be searchable by date.

6. A Journal shall be able to be undeleted within 12 hours of deletion.

7. A Journal shall prompt a user to delete old journals if there is not enough space.

8. A Journal shall mark days that the user has not written in.

**Calendar:**

9. A calendar shall be able to differentiate between todo lists.

10. A calendar shall have a weekly view.

11. A calendar shall be able to transition between different views.

12. A calendar shall have a QR code that will allow the user to view a mobile view of their calendar.

13. A calendar shall have an add task button allowing the user to add tasks from the calendar view.

14. A calendar shall show the main or sub-task completion percentage on their due date.

15. A calendar shall be able to mark tasks as complete.


**Account:**

16. An account shall be able to undelete a task.

17. An account shall be able to add new subtasks even if the parent task is complete.

18. An account shall be able to sort through all their tasks by percentage.

19. An account shall be able to sort through all their tasks by date.

20. An account shall be able to sort through all their tasks by subtask.

21. An account shall be able to sort through all their tasks by main task.

22. An account shall be able to sort through all their tasks by amount of subtasks.

23. An account shall be able to add an icon next to their task.

24. An account shall be able to color code their tasks.

25. An account shall display how many in-progress tasks the user has.

26. An account shall display how many high, medium, and low tasks the user has completed.

**ToDo List:**

27. A ToDo list shall be shareable.

28. A ToDo list shall be importable.

29. A ToDo list shall have a QR code that will allow the user to view a mobile view of their ToDo list.

30. A ToDo list shall be exportable as a static PDF.

31. A ToDo list shall be printable.

**Settings:**

32. A setting shall allow the user to change the app from light mode to dark mode.

33. A setting page shall allow the user to set the default dashboard page on login.

34. A setting page shall allow the user to set the default view mode for all task views.

**Dashboard:**

35. A dashboard shall allow the user to see an overview of their completed tasks.

36. A dashboard shall allow the user to sort tasks based on due date.

37. A dashboard shall allow the user to sort tasks based on priority.

38. A dashboard shall allow the user to view stubs for their tasks on a mini calendar.

39. A dashboard mini calendar view shall allow the user to click and mark it complete from within the view.

40. A dashboard mini calendar view shall allow the user to move the task at different times and dates.

41. A dashboard mini calendar view shall allow the user to see the priority of the task.

42. A dashboard shall allow the user to toggle between different categories of tasks.

43. A dashboard shall reflect the newly added task in the appropriate category.

---

## ⅩⅣ. UI Mockups and Storyboards (high level only)

### UI Mockups:  
#### **User Flow Diagram**  

![](https://lh7-us.googleusercontent.com/gaV0fvnNM8-J9gCzW1tiQ5awkAqIuIRpSrrlzyYlPRy49vVtyKItiwfWhED5KY9AdLb6ASfW_MhKR4s3BQM3KseURwGDIFG7_A6jPQjdXp3-IvAYxGscTKlUsvVZhwttDj3Aa1cxQzcx3FpiMFksjWw)

#### **Register Account Page:**
    

![ | 700](https://lh7-us.googleusercontent.com/_wbFrNB1sY5uBsZYqaHeP6-Szif0yLzomUBCwl-JRuh1mbrtJosHY42TLYlA7avzdFJCzRJN15ee6WIP_AdON1wxJxCkO6iDfzTgMLO4dzGcRLoRGQfoD5xpDkMwvAEydV3t9VFrNdULWXg4o-kAYKU)

  
  

#### **Login Page:** 
    
![|700](https://lh7-us.googleusercontent.com/y8V8eczOQEHBzYOOzj1wnKyvEJkLioemx04AvvNXvoj4Sn46sRwK2TOKkNWP79Pf--8rzDK1-LrtypiZMG2rnGTqYmmPNsJulVn7NpdRGAgCHZhf9982IYHgt7eLxepDSIF4kt9vZYGHeDsKQSK9gAU)

  
  

#### **Account Page:** 

![|300](https://lh7-us.googleusercontent.com/Nm4wJorPCLhOF5zeH3FbUFqku3AJB-ysFi8zv_MlagKRjcZqGvxjQxSMQHR4y8cYW7D9RBWG1WWmVYVLRzq4H6c5SS3C0YNFevP03kvLPURc1GjQbTRRvGM1HGN4gwwrIrCpjtTb2pK5OAAZnEpQMkI)
![|300](https://lh7-us.googleusercontent.com/AEvbN5lM-ujHpwYTU5DwOzIrw-Hs6PI2n4fePc1DWRikhOiGvNJhmWWAkAlz4Wc4PXQhqsJrK956ipN7KmPTT6pGgqeNincwkg4eeBn78UfpJk7pvzHEf47b7qoCt92XsY85tnQMO5EMzCKEUsSqJuY)![|300](https://lh7-us.googleusercontent.com/CZSlI_sr317sn4zVj73ZjL7GzneZz4ePUTytULzxvQYcEiC46ZLErsbyToBDiEpGQoVF6I6WRSVq5N9jJQe9DqHu4I_6CGvzS8JQ-4PvO25iOphtFOVHj-xxLtXF9lrTs9knvrA0PRrhvC8Qhe3RlbQ)![|300](https://lh7-us.googleusercontent.com/JzU6qnRqQxQZJxp5X6TJXfK2A6TI7pr1XdJQ55SnZ-0g1pvih0OuzKqNRoBQVJYEVG6sSMKq3CPiNq5srUUgztBB4vvVSr_GqSvw5Td8jiB8OJ8xyJrE_D2ph_HpZ0QT5imDOtTUfjRvME2gkomPuUs)

#### **Empty Dashboard Mockup:**  
![](https://lh7-us.googleusercontent.com/eEATIps9qzXa_n5Kw_lgHBdqpcZ4rJ-c1UmNdwzIzNfBDbPSXwPssBNj2IEWKSuU8jK4WLLDc7fNdq8EaBJw1YpZrkU8upne_nHx5Gx0FZE5a2mtC3jv0IThkzTafV3bB8rGxozYMrowVbyRpVriE2Q)
    
#### **Dashboard Mockup:**  
![](https://lh7-us.googleusercontent.com/CEf_CMU7hnZqneAGIx7lxDwAPIXi_WkZ0U3d8gemiTwhr0To39FhD8NZv1JHFZa9xBRKLUOHn61JbPR7-yV33ijjgNXsbeb-leSfV-PsrhlWRK8b4x7vYPatM_VnZkRG9rOtyw3hIBiJEipJgHxeh4k)  
      
    
#### **OnClick + Main Task Mockup:**  
![](https://lh7-us.googleusercontent.com/2xOIhh0QrrPbooi32rnYDX0CRHbvT1RvsPe_azXA4_D3tSh-bfC-NzMIgj33kAYe5WQDw5PatRUyo1mXP2nNcyp6q0vlJRbDZo0XfC-QWaWA67sP9RgG2FtgTIuKmHkAacFIoILF9B4arQBLV9l0AAY)
    
#### **Calendar View  Mockup:**  
![](https://lh7-us.googleusercontent.com/ZesmrB1yP1lbgdNd_u180dAiDuWJARbCj5XVpzXANmSHseOACQe-MCSKdax6ufUtpN9xwXkm3ZOHnOg9fo7ZtJF_dTYnV20-DwTgTqnHGu4HJq7msuB2hxAzRkfim9Evtqy-iot1vvGlHkr8g6_mvKA)
    
#### **Journal View  Mockup:**
![](https://lh7-us.googleusercontent.com/PsEpM8BkwsuZexDNmNiITbarC9m8m63FCcNYjy13RSRYec8RBvp_0WJ_p0YorMzZEN0lxpIAo3rmkZfJaFqwLEM8yviKrClNcKB1g0Dl-c6ExG4kdhZ0XcLGGLIzFT3yKt77katN4iGySZKggyKddUM)

![](https://lh7-us.googleusercontent.com/DJaSQQG_ytEbcTCYbSKzRCu1HX6cjvd0leWnHZGs8a5srq3IY4Xyn55yuE9qA7W4-l1IVQfjUfGe9YXODdaeFfLy-IgXTPI8dSMCmhwOF1to8PALheo57zOgBM8wo_Opp0Vp6BaY61991L7dTNIejf8)

---
---
### Use Case Storyboards: 
The storyboards progress from left to right while moving downwards.

**Use Case 1:**
![](https://lh7-us.googleusercontent.com/YdcTcRu-EzcktLWirTFURww8JmROrLI-_P9g7rPcWt2G14y9rGl9-MzaSPOc5fRaiZM6smpp-bXrhraCqReLDdhzrTxZsEYSis2H6wmrVKOIwdPWrrzD7FCEjDhI_M8bAJLBMgceEBSUE-P3gFfPBvA)![](https://lh7-us.googleusercontent.com/reRdCe4D7_g2wWZ0vRzlLlRXs8udWVC0r-0la1vQY7sy1i0UgvQ-K3EU_EXl9M0k1X5PTSXAeGQQd6mjujjcCFOCoY_lEHWgQkcmQzb2wQnVO69FwU_Ul_M-eAaSYkbqicA7Wg6hTTZpE_722Jw2dW4)  
![](https://lh7-us.googleusercontent.com/AnWk73r9c6ripA6owAXsKvtmSRodIRsS7pMYITSVqqIePx_ipsEYDxAiCildd6lfjkzMl0ux6N6xIW-VlZGRx2eqMQTTesLUMgxla0TiXkg8CFvTfnGMRAi5NdpOik9-W_7fpRruqbpqcPha3kfcLSQ)![](https://lh7-us.googleusercontent.com/1Aw2g1I2_fDDgWtfsLtkxJ7t3pON7gu_xOi6chRtlnEC9Cf_s5yRiH2ZfBiTJh0Kw-hsDVo2toNhcg1ZixWF1yhdeK0cqwG886lhdMKLYiEffvUuC3uiWLYiciH2L9eUEpJhpRDrUN5fa2keAAHDiFc)

---
---

**Use Case 2:**

  
![](https://lh7-us.googleusercontent.com/Uykrwov2bA7PqMPsy4GOv5LYRctqjNDjm6zNI-xPrJwarLIB_5kZJup-zKhC-LiBiol0Bwaner0hWMCNRbJCd2KN8Zsb7NdEsoVhvuq3DJPe9Op5sCBP_U71aJl_F_YlI1GSo1QDgQzVMMpyV1jVLD4)![](https://lh7-us.googleusercontent.com/PkhSihgto7Zo_eJkNpJy_oHBvRK-pCYspZg-eM78jIhVQta_0NbalFu201koIRLgvHQU6pmmUO1dEMwFFbXn9tm0bFz1FNCPs9SAk19yhc7wLne-hnIeDiKeuBntNTGUlIMYCOuQRo3EaUNX9lcLq_A)  
  
![](https://lh7-us.googleusercontent.com/-NxKl1YI3L4V2vfnKsQp4k8fU-U0KP3Q5zl9rGrwHSX1_f7om9vViizZGEDGTxBLxKNQ7y5mUB-D-j2E-0BlXZ9C2awgoIw5LFeE1FWN6xZ96VrypSqvXGszjyypzUbuuThh42n4j0vbMx8DO-6tcKs)![](https://lh7-us.googleusercontent.com/Rr7sY-_V1mF8-FES_K0JmhMDiwTtAppKfHLvhv4PPxNAReqBKBvn1i5QhJQkCd9V9JC60prTQMUEYcacNOiOxHvWwA-1QFA03xBCBwAjE3VsBg6O-SeiJIM1fmqWclzkcrXTfjj_-pdf4oyJUB9tSWA)  
![](https://lh7-us.googleusercontent.com/wUKoKXm-pasQ6mV3E_rx_z3CvRVJ-vvxS08mrvy_cR2iC8Y9P2NL5LhDb1WaRcHZEPIwaYNAq14i0jJd8Ijl-rLkM0MVFqfqqbMYC592PfTFi13e2e1TAdASnsOLNItKIIWBud5Mh1_jU6YFUuBeaE4)![](https://lh7-us.googleusercontent.com/IMVajuzmzkvVE0zt_rByQ8YqLlOr4MRpY9lKvqcGKsiK880AFwv53yoJ_GDyD_KyQAhkHNUp6SS8KemgutbPoLzP9ChezVsQ7leSwly5SrvH54lhvMJR2tL-Lmv-GJdqYdQqjs29QptlQx5MFOO3XM8)

---
---
**Use Case 3:**
  
![](https://lh7-us.googleusercontent.com/ked9VTtLvWBr1e0VUQ6dWh-AuuZofIIzPbEszBeVOqYLBBeazn3aGbrFWdoco5QzilDpAB7r_OXsfigB3T5PyePShongyGkZc8_YyB88S64zEfcA9nzDeKJt45zjetIdBtTR-Sv62aRDMAByeT875xI)![](https://lh7-us.googleusercontent.com/e75zG7iWwFW2PMaePTrCRPeSXbmE7yjvfdqAGvFTxmMRvg2bZYHMbS3rT3ABgmpc51Nnqk-QGTORvUpRfrvKiYrVgDamGjuviu7w5JEoNbarVqD5sHmBg7Agb3QSOtsLKsM-ypsBOTLeglTgJLYeBq4)  
  
  
  
  
![](https://lh7-us.googleusercontent.com/c18ukgE2BWA9Poivc8V-rK0gpaDyrcsVls40WCIGXXiVgweKzfWsEsm7f1fban3_x5M0uKA-qtCMrfWwo6f6eYGh50synDSsH6KvAoxxV4M87L_5TnoEgb0abR-68H82-QIaQtKyyYGSYuAXf3E5Nis)![](https://lh7-us.googleusercontent.com/dYoPmkeHhXPcstH8UVFT8aELHBDaLhrvjZTaZfXKYL5NUyHygvFI2BnX_75AAh62MPvRA_ugoenSdWlY7Ps5916bxn0xZBp_icqcWfzN_58_FRlFOtolIC1CgtLjPX_UaRIvR8RPBOtydU6xJpRjOvw)  

---
---

**Use Case 4:**

  
![](https://lh7-us.googleusercontent.com/55X1OumDAi3x-kgNf4Bqn-cGFRqO4B4ZdOLRIWvU4s5LWjKLzOg9qoVf4LqQhhvY6C2zJVJSnrnl4RkUOwIUgWvYBbj_175CxhF0LCC9sS99JA58T2pL-d8NNeU1c6tejbEGW4MwGvE-CWdC_yHIcPE)![](https://lh7-us.googleusercontent.com/xjahmFwQWQtPKpEhfWq9Qo80dmU2Y7LVubv1_gdbfC7_8PYcrvBAZC43lgDKnl2YQYCEi9gdBGB6GCsC9qpcLlQEJyLSFtLrCB8RiOQg5rGH3qiKWux6uyzy_VQi2VCUm9bEAJTqBuefgXjQptX8i38)  
  
  
  
  
![](https://lh7-us.googleusercontent.com/u5smint0zCKyPBmF8FkumX2tYjGFxhUCeMqrlJbIn_uJCFyZIlE5YgGNj-RGEcWvKVXaJbxfgvRSDsSbWeRTNvtKSEDEevM3gpAwAdwt8H6l7H0MwSb8l-9W07_XDUaBl78bhuTqf4xMk0Gjv0M9KtE)![](https://lh7-us.googleusercontent.com/tLDKq7DPd558TG6Oz3jcZ5_kN_DpwePNXgNp6uGwJEuIYcRLRrdOwlxZOzdvARQ2G9nlEV0S4cHPiwBiOLcfGgHZoIAzeQiXhCLSyFxp4GI6pVpk7ZfKQFUKjYDS3MsW7c6HmEPEBF8uUTPdLq9za4w)  
  
![](https://lh7-us.googleusercontent.com/eHZwIw8JQykc8xix-m7qVOjTay795chTKUeAWXSr7Km_ois5JE6qi6vVFGxM_IpEYf9np1iycw8Hmem2Gi-aVcTE6O68r1s6XJmfMlGwb3iTwC5JJ5Q8-8dRKVArV9dRPlwLx3G4AH1yg7NtyN7wOv8)  
  
  
---
---

**Use Case 5:**

  
![](https://lh7-us.googleusercontent.com/_TjFqHjfhZ4KpAckzxqJuvdMuLkCuMrKySLar8Sf-rmFgqM08j610pELNs8VmIjYOYzRQpnx5KF9d5IZhFtG52qEKJhvhQlfoyceUx4qejFOyugTW0S1yvZw877idjWXxqdgoy9-KFgny948mHj5BZA)![](https://lh7-us.googleusercontent.com/0JobwA5mbBM6YVx1VIPrv8gEkjaXRsqadqu5OitRf5GgoKL9ZfaZhKUZK_aLC4mBKrARVWFudWgkHxVd9-WeerVSPjbiJAuL2xZ0ObBYuNCS0ZU4_QymszZVqjft5gT9NIotSoBJEf1Oqr7lncdzsMY)  
![](https://lh7-us.googleusercontent.com/AJ7uZrIH0GesYXa_338G_utF3DEBUOLCMxyPHLrTUtsn2rqcvTj4K72HPOR7hOgOxYaflNFSgNUllIJd-Kf4pFGVMfGbFCPzIUPhkf14vumkKWgUIBEDBkb5FA5GE7PgmdS1ZhuO7hL5R2lj5frYFqU)![](https://lh7-us.googleusercontent.com/6U6xQw-X8AKARQVp5NbEx_-kdl-NQ05BdKFot_kKXlaaGotJLTPZuXhTyp9G5CVCLqv-V7cTJ61p3wpZjlFeNerFQ04F0px8Icfb4RYsNI0qX43BzQh1vcppq4A8cB-JHi-s1Xeq6isKIqQxImnSXWE)  
  
  
  
  
![](https://lh7-us.googleusercontent.com/SkBqhd2fDNrCD51n-O8kSmYg3nwLF0CvBGZj0gDsijLyUIG6KyPZLo1KVbtPTzI-Mwli-GP4EQ0dhRPSWxMYCCk9QjXlGcag4q5WOn2vfcogh_ZBtUUPGj8yKBd5xiUPxFDKEj-4bIG2ZZjzTYw4qDA)  
![](https://lh7-us.googleusercontent.com/1Pn36jUG5snPn5x0zmeNH4za08-m-SuTXJLLh_kFj6w9_W_86YG2ot7yM1yyW3fCb9NnJ8MxTV-glLASkrCJv6SkCz4dGNQ0VUVQyvxZiebO3E1xetI1Mb4Dpb29BlQXDvd_Rqj-NwyRQzEDaXBcEkY)  
  
![](https://lh7-us.googleusercontent.com/uB7qrjPCwg-tydOSagF8HO44LACh0UMgwti3TboHp90A11P2V7KlSNEj23NjwOaO2l7w90cO1L4X-ldTDu_3KT0FT7_ET_7DVUSSlxIYIksmxglyrA3bOTU-kFK05l58_YCADImWUlqK95d22K84S6E)  
  
---
---
**Use Case 6:**

![](https://lh7-us.googleusercontent.com/ewqe5o1RsiOi79OO9UTGw83s_RhFHBF8jSuI6Aq00AK1quGdUEWg1CBCruv05K8Lec0tzN6vbklEe71Z1SVMdCXXr62aJh1BZ8G-fM_DIOI_7X-rBNvtUQf53LuV8JnhRkZOih8-QkqZoBJG05PA1zQ)![](https://lh7-us.googleusercontent.com/UgjNB6AyFQnhM14Zb-LCKRe8TzJgnvbag3Vi89MLvTiKzwo3yfARTcqa9sSPBySoYQH7URZYg6LPKCjYp3J5Jvk8dR0uQPboRQcEpXKyrJEU1miTQP9xOeE5KhVzjv0CyUUty-3-vnTr8aiBoLRJo68)

![](https://lh7-us.googleusercontent.com/XDmtoKQwRrJOIZiAnAwxorpdvrmkoZz2woacjYBe9_hU1HQ1CiZbr2ZvKfYzZhZ9KX25lGFrR93p6Pj708WumMjOwjdW7DGxi-hUr-MnHrYa8-P6THDmojNpSleRG-2uPSX_XmftDNwbO0XUvX1nkLE)![](https://lh7-us.googleusercontent.com/zI1G_V0tS4IT2krvPngbOs65HoS4Hk6XivOiiOxFQBj09kfT2WNPBfyJ54AIsFfwHd0hr8-UvQxG57FwCIoHEXyYtk-lUWaz21JD5lxBoxMQQYm10CN1G0Cn9BiZpybWgEwxhAIjHAZNnkLi26aCW14)

  
![](https://lh7-us.googleusercontent.com/2XmmdLcBLQWGcSu8ECGFoDwyH2UYPL5dO-YPuHZsZWPer4Dd_Q_YL1ULhoXSYlUY29tHBZroXyomsNgseu01EPTcd-GWJcRTvAurCwc6XmRgK9Hw8a-cXJFc3QxNNzUS9BVbMpX_1TruagMue81mJXA)![](https://lh7-us.googleusercontent.com/O5TD6sxhThb-baPVcUNg9cDU1BkR_o3C40rKBX7W7xe0mdJFYUFhzCnuzXAkNrpY7Tcbcw7vKnkTKYEcTPjd3qD_sR1_u34263aZZ5d2dMd9WHgaxSfoAcrhI_8vpsLDU6MtRsdCs2txXgJ4ONA1Jms)  
![](https://lh7-us.googleusercontent.com/eswqGaXd9WrxHXeG9ADNABdLDSK-x3Se6oHclvI3AFGQL1yuymVBbb0dqhVVW29x5ZYzigufdid4-eK371pMzm5_SOTu1WaZZZbWwceHpQ73AjeGsZJzZla-l9YMYbvsmyNBWtiI7JMnbn0OMGbVxDE)![](https://lh7-us.googleusercontent.com/zbXc04WShvTI6OiC2uqFn_M1YwXb4rbCl0kW6-4bcmNjbLmiMWlwCemUrnDOPWzuPR_mpq6q7z3htJZyDofn1430fEZTYc4et69JUrJFYouyVzM9FEAF_2Lu5UTgwl2ibVU5pKjMiXPSO-lfvnzdWd4)  
![](https://lh7-us.googleusercontent.com/KxmOIcF_LUAEpwTDDgFpcAnNXzCeqgY0g69zMzFN3NrG8mgcGIroo0GOvuDeDgtunXfmTm7OxUjILDzPpd7cawhecp_tzzj_GnqQxR9WBdKB1dJ_TbrA0Y8cs2pReamHx0C7qY8cie0-33ZSngc5UfM)  
  
  
  
---
---

**Use Case 7:**
![](https://lh7-us.googleusercontent.com/FNskiUISU6xTnbOsqP-Loj5ST4cwfx687qLreHFEW5wpgcPffX3-HO04IFKgTCEjL-qsF7KQXkTN3cE0rdOiJJ4mLYH-TOHKa2LJoHezHy5hpYpeNFSTNRfCpWKMPEL90Q6eg6VKhQr61KoaYSCpl_Y)

![](https://lh7-us.googleusercontent.com/TYUNMvbxFXjKLJWiELJdnUvJ8QotVk3nvXOyQPo_ypVVgqFl9ZqKj0Gv2rFhkeafDpWMoSY5TCcYuHOUL1ZxrS-_SOyqLBntR67eunTNBkCVGyb4l2FDW0xh_uZXRKbvsZe0AyFArOv2ICpyLyJMKiE)

![](https://lh7-us.googleusercontent.com/8PLtdQUd-TqLazvoubrzE85N4rdAWWG3QAy55pNNvMGWSNCbZzO9hEq6W8FJubnBSxQVTcebFdvPy8p704pu71SU8HCDfe6bqD0Nv0hN74lq8itYXaveZJwBepLEq47c4EK5gDRqMi7wkHg972_Liac)![](https://lh7-us.googleusercontent.com/YI54mOJbuC8K5xsDrgh8S6hXW70cfN7MwKVNtkTx-a8T9YKYElBCzQHJhDfnRQJfGfFB9RDZNianzQpZq1eyIS8HTwDIiQYsCSBG_TWLNBo-qUS8uC6hM68g3BBpoXERz3wlZqFTUjj8OG_usA1klNA)

![](https://lh7-us.googleusercontent.com/Yiz5cAUqVcOiIqgXlMhrWNokgBtnC9Vb-PBroDh8d2f5IYIGU_oCq3Jw7oWM8BQRnnlem1nhRNVo-7Sef0DiOVioaQdtqUQTkgh7dki2csaVsGYW8W21-IEVUmi6JufvE7xSS7e2W8QIQaGndsiqnug)![](https://lh7-us.googleusercontent.com/wnVuQjYFraw9fK0klKWdIGwvoewvWXoO2uHX2DIRpugo5XIQK_PzZgzCno40eMIuhtqHkjznofJQldBfAcL64K7YGJAeFgnCJcpz465L3atZvupzzaraMh_ojaHqXYO3Yg58c3ZluKBdWrKzctVO53U)

![](https://lh7-us.googleusercontent.com/cT1G5NLImhZMEIxBUqsZt_3rLVsQnk41gTyCETpivr5SPXMAroUaVLlvhpH2m9X39tTKlWg9mkYgQzsaIcpKjfyM0z-C93OuYnOTc7GTmcFI9ybGmp5sPXhXqxr_y7XPVTVP3eHoYJYwZBl_fkHylEM)![](https://lh7-us.googleusercontent.com/pwq6B7J72SCRO6u6xfExpCJmB5K4TzbezF1g4_VLSq8q1JqKoaZ3eld5BqlbU8Cm2zPQ_fJV0nYa8OV46uwkwViz2RjIDsXFaRFKsUa6A4y7FLddW3dNdm4aak43Lxqdkbuf2N0OjPLxYjSzMmCSaLI)

![](https://lh7-us.googleusercontent.com/FL3GvB2g6_S1Xj53XoRFQqcby2TGmIquzqG3jw-rISmelauvozgos1M8WkYlx6oRq4jJ2hl0nj1m5zTrMxIG406CRmQVxLF4e-6uGqYbjtAobPTouFLkgUE9AGGVI9dnJrMRObHyZsFWM-l4p_gcvec)


---
---

**Use Case 8:**
![](https://lh7-us.googleusercontent.com/kqyOOArjpip5gQm5T498o2GKqhixZDR2hyRWAQnrZ_rIZK_o6nt7DoXVtGWUjeFL4SxJC-ah7jf5gN1YJyYJ1Ul2PkZAI6GTTV7GeyZpI2VdL_L5tN318j21S51_NL6yqhvk5tm1CtMagMlrKv6pMfg)![](https://lh7-us.googleusercontent.com/w7MRPXqnxZvbD83n4obbePKqtC9bfcyzQkPkkuO04K7YNJczNEepm84BYK-FhnkVzkTA76GzzAGEsyTd8obbzi-ZtQOQc1gPaLly7_p9vju4qigZXhmMXs9c8NxEpWaMba5_sGlowomHe1Pw2OjtfEQ)

  
![](https://lh7-us.googleusercontent.com/6l7KpW6nv_JNdXMSgiZeCEYgDmu6dISzU0bE7QzpQ5XL2Xf34yLASz-qYiTiJdqOtulN1UDiiKe1XZut_ETcGqLBZblLQH5bAHRSeru6aorG-TbYL29fCGpnUBp03plyzg1FqF6Gz6Mse_LVrY-FfSg)![](https://lh7-us.googleusercontent.com/lopsebnXMJ06WtSyYT8f8MhB_LVLzr9fn5bRm3nO6CwiOvvegmQB2UD3KFAMjI9IuT8TUIkrKU4_G44wB9RymMI-6daYC1jqQ_EvIHcp7aKXQRXwT0RsPWfyunIqLX9TFv6ti4fBhAMMVNhMC74Ilt8)  
![](https://lh7-us.googleusercontent.com/hx5zPbta5k6tagI0ZHoTULKp--PMxx6sK9h3WhgVLpDIEGT05VeZWM4gIDIajLFeQMaIPJrdnFSaU2dZXgLmmRm6q7lYf1zsti1wC4wQROOzbHHJ9FdfNjPY2_UgEABr5GADw2Gby2siGsHOjkE-9Ks)  
  
  
---
---

**Use Case 9:**

  
![](https://lh7-us.googleusercontent.com/l3keDFzQFMNkFGg8I-cWNiDZZanJ3JLgF5g2lMi6FFzc9oRKQtym-6IWqHiMTj2odQItQ-Jrzasrp_hwGD7Kt4lRahvwakZkwg-VJC_ta7XLkZ_rH9VvuaPJL0rdySEH8IBsvZtQWSi4cu9lXzBc4FQ)  
![](https://lh7-us.googleusercontent.com/F578lo9Dg5mAjk7QLG2T2fjmLieSaL2lbhqg9fbnlM5M83bggDYG3qyYDQcHkCEWRqGQtur3LJy4BK5Jlm0krHrVp91oL8h05tfoQce7gy6sD56RuRAKO6Lm2q-nIBXt3dwW_bBzMtbW72bS5FvXtlg)  
  
  
![](https://lh7-us.googleusercontent.com/N7xAz8_SlVr6l99RuYeC3sp2MVhIeAWkk_9tJ2QoM9xrss_qbmmjEKXo7VeWKnRWeRV5ZBTRIOEjhOQk75wyJmb6slHOwHt8YP1Vogcdbwf4wsMvlY6-TBYiFdojuC-bzTP71JCoHTm2pKxB0BLbSA4)  
  
  
---
## ⅩⅤ. High-level database architecture and organization

MySQL is a great tool to use due to its ability to efficiently handle the relational structure needed for organizing entities, such as tasks, users, lists, and other entities. It's also easy to use, as well as having the ability to convert ERDs to EERs easily and can export the actual SQL database

**ERD:**

![](https://lh7-us.googleusercontent.com/f5R9ZX9rREFy3o5mPyAST9C7S57h1UHaLft62JEKaRHAbs3O1OuYTWMdN3Vp9QUyDKTPr2b0-UQGKNjzMXC3OOgcWZy7nBrnuGUDMePWKt5ukP53YUCfy0UpkkguTK4d7TmueWVX7_85QCaUFbpXJy0)


**EER:**
![](https://lh7-us.googleusercontent.com/ryQhm5RxdFWbYXtUGPKS8BvDplnSUC9-Bt4Hk6NerxPAWaJb8jUP14FwX5mnQShmX6AdKJa-bVHicNU87tMJkxg8LwMlSij18efItWWB5_EhhWREEgSMk4NDtbncG7UNaql0h1z4FqQe3YEGfGBtBO0)

---

## ⅩⅥ. High-Level APIs and Main Algorithms

5. High-Level APIs and Main Algorithms

- Priority sorting algorithm
    

- Sorts subtasks based on priority but only for layer. Each set of subtasks is sorted independent of subtasks under a different task.
    

- Tree search algorithm
    

- Searches the tasks and subtasks in the tree structure of our todo lists
    

- GPT2 API(HuggingFace)
    

- Calls to the GPT2 API to generate text for our prompts
    

- List Search
    

- Basic search of both the name and description
    

---
## ⅩⅦ. System Design

Scalability Diagram (Zoomed in sections below):![](https://lh7-us.googleusercontent.com/DtO9CDUN5CDlwIAHIH0UofEf1Lt2I5XYG8ONwGYfVVuTr2ZdY53p1x7MNABtji1g08RXhaOTXth0CXPQEGoEpC8gA39rCvKc0q42qKa5TwL15eDeziaJbYcgytvm9zh6ttIm8qoSCf99izpGRKcinNg)

  

![](https://lh7-us.googleusercontent.com/MpRYH7yxh7jyg3a8u3dX1jW6kHKCnqj_zQiI2Up9dwywWCURqj7pidL3lGhcgIYb92fCm4Q3bl2YhqArM8n-JbQfU-62_ayQwi3fzzzVBEDnQZ7poi3CoJrNgTyx4kF5TlEVfKYd9x6bwhF5wCMSsKQ)

![](https://lh7-us.googleusercontent.com/09vm56R8U-ootOAZOq9znx6jYfuUdW3xYW0-lNvlU8sEK4GehSZ2ntAbJKlV7rQ60LJEat4F1ZYopbXntCN8mwScHAGwh7YJRlBm6EE6juPFRZOKDPNKn9sGPJrO17iFbfiwFuEyPr2zoc18Q-FytEM)

### **Scalability Diagram Summary:**
Starting at the user end on the left side of the diagram the first microservice we're using is Amazon Web Services elastic load balancing to manage incoming traffic for the instances of our system. Beyond the load balancing we have 3 instances of our application one on the East Coast, one on the West Coast, and one in Europe, the reasoning being that no critical failure could have happened in all three locations simultaneously, which makes the entire system much more fault tolerant allowing for an entire critical failure in one of those regions without interruption to service. The next microservice we would use would be Amazon Web Services Aurora data cluster system specifically with the MySQL compatibility. This allows us to keep our same database structure but replicate it over multiple instances with a clustered volume backup. In the version that is in the diagram, we have one primary instance with two replica instances ready and immediately waiting to take over if there is a critical failure, along with 6 supplemental copies of the data. This gives us an incredible level of fault tolerance and error correction as if something goes wrong or something gets overwritten Aurora is designed to be robust and have safeties in place that will help us recover in the case of accidental or intentional data corruption or deletion. Another advantage of using Amazon Web Services systems for our upgrade path is that it keeps everything in one ecosystem. This unification of the ecosystem means that all of our systems are in one place which is convenient for maintenance and upkeep and also is a potential security vulnerability depending on the security for our login for admin. But that is the only major drawback is that since we are using only one system if Amazon Web Services goes down so does our entire application we would have to recover what we can and then try to transfer to the Azure cloud or some other system but we would lose significant time as everything is integrated into amazons web ecosystem. The main advantage to keeping it all within the AWS framework is that this basic structure is scalable so if we need more space and if or if we need to increase our throughput we can add new instances and increase the redundancy and distribution for our data cluster very easily with just a couple clicks. If we were using a disparate set of components from various companies it would be much harder for us to scale up and down depending on usage. If the application becomes extremely popular we might need to migrate out of Amazon Web Services into a more proprietary system and that will take a lot of research and development time but for the current scale and the current scope that we are looking at this should be viable even as a phase two for development of our product.

---
---
### UML Class diagram:
<img width="2400" alt="TodoToday UML Diagram2" src="https://github.com/Sulavjung/Sulavjung-Documentation-for-Todo/assets/79497159/2ffbb0ce-ddf0-45ef-9443-7bc647b6efd5">



### Summary
System design patterns are categorized into three types: Creational, structural, and Behavioral patterns. We explored different design patterns, including the Factory Method and Singleton patterns. 

While suitable for creating objects of related types without specifying their concrete classes, the Factory Method pattern did not provide the level of flexibility and customization we needed for configuring `Account` and `TodoItem` instances. Additionally, the Singleton pattern, which ensures a class has only one instance and provides a global point of access to it, did not apply to our scenario. The reason is, that it would limit our ability to create multiple `TodoItem` instances with different configurations.

Other patterns within Structural Patterns and Behavioral Patterns seemed the next step for the scalability. So, after evaluating these patterns and their suitability for our application's architecture, we determined that the Builder pattern offered the best fit. Its ability to encapsulate the construction process and provide a flexible way for creating complex objects made it an ideal choice for constructing `TodoItem` instances with varying configurations. By adopting the Builder pattern, we ensure that our application remains scalable, maintainable, and adaptable to future changes and requirements.

## How are we using this pattern in our System? 
Here is how it is being used in the above UML Diagram:

1. **Building `Account` with `Password` and `User` Class**:
    In our system architecture, the `Account` entity comprises user credentials and personal information, which are represented by the `Password` and `User` classes, respectively. To streamline the creation of `Account` instances with varying configurations and to make each class responsible for small tasks, we employed the Builder pattern.
    
    The `Account` class serves as the primary builder for `Account` objects. It uses the construction process by utilizing methods to set the properties of the `Password` and `User` components directly within the `Account` class.
    
    By utilizing the Builder pattern in this context, we ensure that the creation of `Account` objects remains flexible and maintainable. The encapsulation of construction logic within the `Account` class and dividing the responsibilities across multiple other classes simplifies the instantiation process and promotes code readability.
    
2. **Building `TodoItem` with Different Configurations**:
    Within our task management module, the `TodoItem` class represents individual tasks with various attributes such as priority, status, and due date. To facilitate the creation of `TodoItem` instances with customizable configurations, we adopt the Builder pattern.
    
    The `TodoItem` class itself acts as the builder for `TodoItem` objects. It provides methods for setting the attributes of the `TodoItem` with `Todo`, `Priority`, `Status`, and `Due Date`, allowing clients to specify the desired configuration through method calls.
    
    By leveraging the Builder pattern for `TodoItem` creation, we ensure that the construction process remains clear and adaptable. The `TodoItem` class encapsulates the logic for building `TodoItem` objects. It enables clients to construct instances with ease while maintaining code's flexibility and maintainability.
  
  ---
---
## ⅩⅧ. High-Level Application Network and Deployment Design

### Network Diagram:
![](https://lh7-us.googleusercontent.com/lZev_uSj3YacYArD8I7gvkHo7BNdwaNnkeqjXZAqTi0yrh_71vwLogJy11urSVdEbNSVtwIvzh_nkXk7dMMPZPFz19knjbZ5ud4neXlPmflJgD0hfZ2cpsf-xA1eRhGIpcSQUCEexltn-_LBg6Sf2rM)


### Deployment Design:

![](https://lh7-us.googleusercontent.com/KwWdZribHbV-3_dye9-x84ryM78n2jXlfBRx0X8IahRGlNJxGVlHprd2bYrOBwp0Mk3AcRJz76-HXzDiN3Z1Bg3hJqTCLUkv0gs8BQuq13m21P4OmXwkBKZSdq9cbfgmW2tfz0nAZNfVZ13W0SbdCV4)

---

## ⅩⅨ. Identify actual key risks for your project at this time

Identify only actual and specific risks in your current work such as (list those that apply:
• skills risks (do you have the right skills),

• schedule risks (can you make it given what you committed and the resources),

• technical risks (any technical unknowns to solve),

• teamwork risks (any issues related to teamwork);

• legal/content risks (can you obtain content/SW you need legally with proper

licensing, copyright)

**Known Risks:**
1. Application Network Diagram Knowledge (skill)
    
2. Initial lack of AWS knowledge (technical / skill)
    
3. Chat GPT (technical unknown)
    
4. Data Leakages (security risk)
    
5. Lack of communication
    
6. Lack of knowledge regarding legal terms of condition content
    
7. Difficulty in splitting up tasks  
    
---
## ⅩⅩ. Project management (Team Lead)

During milestone one as the team lead I used an excel spreadsheet to manage our time and completion of tasks. It was a very manual system that I constantly was having to update as I was the only one with access to that data. Moving over to notion that allowed me to share the tasks between all of the teammates made it much easier for us to understand exactly where we were at and who had finished what and what still needed to be done. It also allowed us to define subtasks and build out a solid structure for the step by step sub steps that we need to do to complete the larger pieces that are needed for completion of our milestone 2. It also allowed us to divide and conquer in a much more effective way than me just sort of handing out assignments directly I was able to hand out high level assignments saying OK you're in charge of this task you're in charge of that task and then you tell us what we need to do to help you. That sort of subdivision of Labor has significantly improved both the quality and speed of our work.

---
## ⅩⅩⅠ. Detailed list of contributions (Team Lead)

|                                                         | Alex Nikols | Jason Tran | Sulav Jung Hamal | Jadon Hoang | Randale Reyes | Christian Gopez |
| ------------------------------------------------------- | ----------- | ---------- | ---------------- | ----------- | ------------- | --------------- |
| overall Code                                            | 1           | 4          | 5                | 2           | 1             | 1               |
| overall Documentation                                   | 5           | 4          | 4                | 4           | 3             | 5               |
| Data Definitions                                        | 2           | 1          | 4                | 1           | 2             | 4               |
| Prioritized Functional Requirements                     | 3           | 3          | 3                | 3           | 3             | 3               |
| UI Mockups and Storyboards (high level only)            | 2           | 5          | 2                | 5           | 1             | 1               |
| High level database architecture and organization       | 3           | 1          | 3                | 1           | 5             | 1               |
| High Level APIs and Main Algorithms                     | 4           | 1          | 4                | 1           | 1             | 4               |
| System Design                                           | 4           | 1          | 5                | 1           | 1             | 2               |
| High Level Application Network and Deployment Design    | 5           | 1          | 4                | 1           | 1             | 2               |
| Identify actual key risks for your project at this time | 3           | 3          | 3                | 3           | 3             | 3               |
| Project management                                      | 5           | 2          | 3                | 2           | 1             | 2               |
| Vertical SW Prototype                                   | 2           | 4          | 5                | 2           | 2             | 2               |

