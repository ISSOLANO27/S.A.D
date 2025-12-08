# Chapter Introduction
When you finish this chapter, you should be able to:

- Explain project planning, scheduling, monitoring and controlling, and reporting.
- Demonstrate the three activities of task management.
- Summarize the five key elements of people management.
- Discuss the five key issues in communications management.
- Describe the importance of technology management in systems projects.
- Summarize the three areas of concern in financial management.
- Explain why risk management is crucial in systems projects.
- State the key benefits of using project management software.
- Describe three areas requiring attention to manage systems projects successfully.

Chapter three is the final chapter in the systems planning phase of the systems development life cycle. This chapter describes managing projects, tasks, people, communications, technology, finances and risk associated with complex systems projects. In addition. The judiciary's use of project management software is discussed. Finally, the keys to successfully managing systems projects are also examined. The chapter includes three case in point discussion questions to help contextualize the concepts described in the text. The scenario described in the "**Ethical Issues**" section of the end of the chapter exercises considers the main implications of raising awareness of a project going astray, even when the project manager is reluctant to do so.

# 3.1 Project Management
Many professionals manage business and personal projects every day, but only sometimes give them much thought. The management process for developing the information system or working on construction project is much the same. The only difference is the nature of the project. To manage a large scale information technology (IT) project, pecific tools and techniques are needed. A project manager responsible for overseeing all relevant tasks is also required. `Project management` for IT professionals includes planning, scheduling, monitoring and controlling and reporting on information system development. A project manager will break the project into individual tasks, determine the order in which the task must be performed, and determine how long each task will take. With this information, Gantt chart or PERT / CPM charts can be used to schedule and manage the work. (Both types of charts will be discussed in this chapter.) Microsoft Project is a popular project management tool that can help create and monitor the project plan, report progress, and use the risk management to make the process easier for everyone.

## 3.1.1 What shapes a project?
A successful project must be completed _on time_, _within budget_ and _deliver a high quality product that satisfies_ users and _meets requirements_. Project management technique can be used throughout the SDLC. `System developers can initiate a formal project as early as the preliminary investigation stage or later as analysis, design, and implementation activities occur.`

System development projects tend to be dynamic and challenging. However, as discussed earlier, there's always `a balance between constraints and interactive elements such as project cost, scope, and time`.

## 3.1.2 What Is a Project Triangle
Figure 3-1 shows a straightforward example of a project triangle. Each project team must decide what is most important because the work cannot be good and fast and cheap. When it comes to project management, things are more complex. Decisions do not need to be all or nothing but recognize that any change in one leg of the triangle will affect the other two legs. Figure 3-2 represents a common view of a **project triangle**. Where the three legs are cost, scope and time. The challenge is to find the optimal balance among these factors. Most successful project managers rely on personal experience, communication ability, and resourcefulness. For example, suppose an extremely time critical project starts to slip. In that case, the project manager might have to _trim some features_, _seek approval for a budget increase_, _add new personnel_, or `combine all three actions`. On its website, Microsoft offers an interesting suggestion for project managers who have a project at risk. Find the stuck side of the triangle. Microsoft states that in most projects at least 1 side of the triangle is fixed and unlikely to change. `It may be a budget cast in stone, an inflexible scope, or a schedule driven by factors beyond the firms control.`

## What does a project manager do?
Good leadership is essential, whether a project involves a new office building or an information system. In the systems project, the **project manager** or **project leader** usually is a senior systems analyst or an IT department manager if the project is significant. An analyst or a programmer analyst might manage smaller projects.
 
In addition to the project manager, most large projects have a **project coordinato**r. A project coordinator `handles administrative responsibilities` for the team and negotiates with users who might have conflicting requirements or want changes requiring additional time or expense.

Project managers typically perform several activities (or functions), including planning, scheduling, monitoring, and reporting.

- **Project planning** includes identifying all project tasks and estimating the completion time and cost.

- **Project scheduling** involves the creation of a specific timetable, usually in the form of charts that show tasks, task and dependencies, and critical tasks that might delay the project. Scheduling also involves selecting and staffing the project team and assigning specific tasks to team members. Project scheduling uses Gantt charts and PERT / CPM charts, which are explained in the following sections.

-  **Project monitoring** requires guiding, supervising and coordinating the teams workload. The project manager must monitor the progress, evaluate the results and take corrective action when necessary to control the project and stay on target.

- **Project reporting** includes regular progress reports to management, users, and the project team. Effective reporting requires strong communication skills and a sense of what others want and need to know about the project.

 Project managers spend most of their time tracking project tasks along the critical path because delays in those tasks have the greatest potential to delay or jeopardize the project. The following sections describe the project planning and scheduling steps.










# 3.2 Task Management
Task Manager in this integral to project management because most projects are composed of discrete tasks that must be managed individually and collectively. Task management involves creating a **work breakdown structure (WBS)**, modeling, **task patterns**, and identifying the **critical path.**

## 3.2.1 Work Breakdown Structure
Henry L Gantt, a mechanical engineering management consultant, developed Gantts charts almost 100 years ago. His goal was to design chart showing plant and actual progress on a project. A gun chart is a horizontal bar chart that represents a set of tasks. For example, the Gaunt chart from Microsoft Project in Figure 3-3 displays 5 tasks in a vertical array with time shown on the horizontal axis. The bar's position shows the planned starting and ending time of each task, and the length of the bar indicates its duration on the horizontal axis, time can be shown as elapsed from a fixed starting point or as actual calendar dates. A Gantt chart can also sinmplify a complex project by combining several activities into a task group that contains subsidiary tasks. This allows a complex project to be viewd as intergrated modules. A Gantt chart Can show task status by adding a contrasting color to the horizontal bars. For example, a vertical red arrow marks the current date in Figure 33. With a fixed reference point, it is easy to see that task one is way behind schedule. Task 2 is only about 80% done and is running behind schedule. Task 3 should have started, but no work has been done. Task 4 is running ahead of schedule and task 5 will begin in several weeks.

Gantt Charts can present an overview of the project status, but they do not provide enough detailed information which is necessary when managing a complex project. Therefore, some project managers may find that pert / CPM charts discussed in the following section are better tools for managing large projects.

### PERT/CPM Charts
The US Navy developed a **program evaluation review technique (PERT)** to manage complex projects such as constructing nuclear submarines at approximately the same time. The **critical path method (CPM)** was developed by private industry to meet similar project management needs. The distinction between the two methods has disappeared over time. The technique is called either PERT, CPM, or **PERT/CPM**. This textbook uses the term PERT chart.

PERT is a **bottom-up technique** Because it analyzes a large complex project as a _series of individual tasks_, just as a pyramid is built from the bottom up using individual blocks. To create PERT chart, Identify all the project tasks and estimate how long each test will take. Next, determine the logical order in which the tasks must be performed. For example, some tasks cannot start until other tasks have been completed. In other situations, several tests can be performed at the same time.

For example, some tests cannot start until other tests have been completed. In other situation several tasks and we perform at the same time For example, some tests cannot start until other tests have been completed. In other situation several tasks and we perform at the same time.

Once the tasks are known, including their durations and the order in which they must be performed, calculate the time needed to complete the project. The specific tasks critical to the projects on time completion can also be identified. An example of PERT chart, which Microsoft calls a **network diagram** is shown on the lower screen and figure 3-4.

Although a Gantt chart offers a valuable snapshot view of the project, `PERT charts are more useful for scheduling, monitoring and controlling the actual work.` With a PERT chart, a project manager can `convert task start and finish times` to exact date by laying out the entire project on a calendar. Then on any given day, the manager `can compare what would be happening` with what is taking place and react accordingly. Also a part try displays complex task patterns and relationships. This information is valuable to a manager trying to `address high priority issues`. PERT and Gantt charts are not mutually exclusive techniques, and project _manageers often use both methods._

Figure 3-4 shows both chart types. The top screen is a Gantt chart with six tasks. The PERT chart below shows the same project using a separate box for each task instead of a horizontal bar. Although they show the task patterns and flow, the PERT chart boxes can provide more information such as task duration, start date, finish date, and the names of resources assigned to the task. The PERT chart in Figure 3-4 would be too small to view the exact details shown in the expanded text box at the bottom of the figure, Creating PERT charts is explained in a later section.

### Identifying Tasks in a Work Breakdown Structure
A work breakdown structure must clearly identify each task and include an estimated duration. A **task** or **activity** is any work with a beginning and an end that requires company resources such as people, time, or money. Examples of test include conducting interviews, designing a report, selecting software, waiting for the delivery of equipment, and training users. Tasks are basic work units that the project manager plans, schedules and monitors. So they should be relatively small and manageable.

Examples of tasks include conducting interviews, designing a report, selecting software, waiting for the delivery of equipment, and training users. Tasks are basic work units that the project manager plans, schedule Examples of tasks include conducting interviews, designing a report, selecting software, waiting for the delivery of equipment, and training users. Tasks are basic work units that the project manager plans, schedules and monitors, so they should be relatively small and manageable.

In addition to tasks, every project has **events** or **milestones**. An event is a recognizable reference point that can be used to monitor progress. For example, an event might be the start of user training, the conversion of system data, or the completion of interviews. On the other hand, a milestone such as _"complete 50% of program testing"_ would not be helpful unless it could be determined precisely when the event will occur.

Figure 3-5 shows tasks and events that might be involved in creating, distributing and tabulating the questionnaire. Notice that a recognizable event marks the beginning the end to end of each task. It would be virtually impossible to manage a project as 1 large task. Instead the project is divided into smaller tasks creating a WBS. `The first step in creating WBS is to list all the tasks.`

#### Listing the Tasks
While the steps sound simple, it can be challenging because the tasks might be embedded in a document. Such as the one shown in the first version of Figure 3-6. One trick is to start by highlighting the individual tasks as shown in the second version. Then, as shown in the 3rd version, adding bullets makes the task stand out more clearly. The next step is to number the tasks and create a table like the one shown in Table 31 with columns for test number, description, duration and **predecessor tests** which must be completed before another test can start. 

#### Estimating Task Duration
Test durations can be hours, days or weeks depending on the project. Because the following example uses days, the units of measurements are called Person days. A person day represents the work that one person can complete in one day. This approach, however, can present some problems, for example if it takes one person 20 days to perform a particular test. It might not be true that two people could complete the same task in 10 days, or that 10 people could perform it in two days. Some tests can be divided evenly, so it is possible to use different combinations of time and people, up to a point, but not all. _In some system analysis tasks, time and people are not interexchangeable._ If one analyst needs two hours to interview a user to a analyst also will need two hours to do the same interview.

 Project managers often use a weighted formula to estimate each task's duration. The project manager first makes three time estimates for each task. An optimistic or best case estimate (B), a probable case estimate (P), and a pessimistic or a worst case estimate (W) post parentheses. The manager then assigns a weight which is a significant value to each estimate. The weight can vary, but a common approach is to use a ratio of B = 1, P = 4 and W = 1. The expected task duration is calculated as follows:

(B+4P+W)/6

For example, a project manager might estimate that a file conversion task would be completed in SVS 20 days or could take as many as 34 days, but most likely will require 24 days. Using to formulate the expected test duration is 25 days, calculated as follows:

(20 + (4 * 24) + 34)/6 = 25

### Factors Affecting Task Duration
When developing task duration estimates, project managers consider four factors:

1. **Project size**
    As described in an earlier chapter, information systems have various characteristics that affect their complexity and cost. In addition to considering these factors, a project manager must estimate the time required to complete each project phase. To develop accurate estimates, a project manager must identify all project tasks from initial fact finding to system implementation. Regardless of the system's development methodology used, the project manager must determine how much time will be needed to perform each task. In developing an estimate, the project manager must allow time for meetings, project reviews, training, and other factors that could affect the development team's productivity.

2. **Human resources**
    Companies must invest heavily in cutting edge technology to remain competitive in a connected world. In many areas, skilled IT professionals are in great demand and firms must work hard to attract and retain the talent they need. A project manager must assemble and guide a development team with the skill and experience to handle the project. If necessary, additional systems analysts or programmers must be hired or trained, and this must be accomplished with any specific time frame. After a project gets underway, the project manager must deal with turnover and job vacancies and escalating salaries in the technology sector, all of which can affect whether the project can be completed on time and within budget. The project manager must also accommodate official holidays, family emergencies and other events that may affect the schedule.

3. **Experience with similar projects**
    A project manager can develop time and cost estimates based on the resources for similar, previously developed information systems. The experience method _works best for small, medium sized projects where the two systems are similar in size, primary content and operating environments._ In large systems with more variables, the estimates are less reliable.

4. **Constraints**
    You have learned that constraints are defined during the preliminary investigation. A constraint is a condition, restriction, or requirement that the system must satisfy. For example, a constraint might involve maximums for one or more resources, such as time, dollars, or people. `A project manager must define system requirements that can be achieved realistically within the required constraints`. In the absence of the constraints, the project manager calculates the resources needed. However, the project manager must adjust other resources or change the project scope if constraints exist. This approach is similar to the What If? Analysis described later in this book.

### Displaying the Work Breakdown structure
After the test durations are entered the the WBS will look like Table 3-2. To simplify the list, task groups can be used to manage a complex project with many tasks, just as with the Gantt chart. Note that the WBS shown in table 32 is still incomplete; It does not show fields such as start date, end date and task name--fields that can be key for project managers. As a result, the WBS(Including some of these missing fields) might resemble Figure 37 with Microsoft Project. 






# 3.2.2 Task patterns
Tasks in Awbs must be arranged in a logical sequence called a task pattern. In any project, large or small tasks depend on each other and must be performed in a sequence, not unlike the commands in a software program. Task patterns can involve dependent tasks, multiple successor tasks, and multiple predecessor tasks. These patterns can be very complex in larger projects. And an endless must study the logical flow carefully. This section explains how to understand and create graphical models of these patterns.

 ## Using tasks boxes to Create a Model
 In PERT/CPM Chart, project, tasks are shown as rectangular boxes arranged in the sequence they must be performed. Each rectangular box, called a task box, has five sections as shown in Figure 38. Each section of the tax box contains important information about the task, including the task name, task ID, task duration, start day/date, and finish day/date.

 ### Task Name
The `task name` should be brief and descriptive, but it does not have to be unique to the project. For example, a task named Conduct Interviews might occur in several phases of the project.

 ### Task ID
The `task ID` can be a number or code that provides unique identification.

 ### Task Duration
The `duration` is the time it will take to complete a task, which is not necessarily the same as the elapsed time. For example, a task that takes eight hours of effort to complete would be done in one day by a person dedicated 100%. But if the person assigned to this task is only working 50% on this project, the task will take two days lapse time to complete. All tasks must use the same time units, which can be hours, days, weeks or months depending on the project. An actual project starts on a specific date, but can also be measured from a point in time such as Day 1.

 ### Start Day/Date
The `start day / date` is when a task is scheduled to begin. For example, suppose that a simple project has two tasks, task 1 and task 2. Also suppose that tests two cannot start until test point is finished. An analogy might be that a program cannot run until the computer is turned on. If task one begins on day one in last three days, it will finish on day 3 because tasks two cannot begin until task 1 is complete. The start time for task 2 is day 4. The day after test point is finished.

 ### Finish Day/Date
The `finished day / date` is when a task is scheduled for completion. Add the duration to the start date or dates to calculate the finish date or date. When doing this, be very careful to add only a few days. For example, if a task starts on day 10 and lasts five days. The finish would be on day 14, not day 15.(`why would be start on day 14, if the duration is 5 days.? is it because we are considering 8 hours of work? so thechnically, the next task could start on the actual 15? please explain`)


 ## Task Pattern Types
A project is based on a pattern of tasks. In a large project, the overall pattern is complex. Still, it can be broken down into three basic types of patterns:**Dependent tasks**, **multiple successor tasks**, and **multiple predecessor tasks**.

 ### Dependent Tasks
When tasks must be completed one after another, like the relay race shown in Figure 3-9, they are called **dependent tasks** because one depends on the other. For example, figure 310 shows that tasks too depends on task one, because task two cannot start until task one is completed. In this example, the finish time on task one, day 5 controls start date of task 2, which is day 6.

 ### Multiple Successor Tasks
When several tasks can start simultaneously, each is called a concurrent task. Often 2 or more `concurrent tasks` depend on a single prior task, which is called a predecessor task. In this situation, each concurrent task is called a `successor task`. In the example shown in Figure 3-11, successor task two and three can begin as soon as task 1 is finished. Notice that the finish time for task 1 determines the start time for tasks 2 and 3. In other words, the earliest that task one can finish is day 30. So day 31 is the earliest to task two, and three can start.

 ### Multiple Predecessor Tasks
 Suppose a test requires two or more prior tasks to be completed before starting. For example, figure 312 shows that task 3 cannot begin until task one and two are completed. Since the two tasks might not finish simultaneously, the longer (later) predecessor tasks become the controlling factor. Notice that the start for task three is day 16, not day 6. Why is this? Because task 3 depends on two predecessor tasks, task 1 and task 2, task 3 can only begin once the later of those tasks is complete. Therefore, the start time for a successor's task must be the latest (largest) finish time for any preceding task. _In the example shown, task one ends on day 15, while task two ends on day five, so task 1 controls the start time for task 3._

 Task pattern types are identified by looking carefully at the wording of the task statement. Words like, then, when, or and are action words that signal a sequence of events. Here are three simple examples.
 New. New.


- Do task one, **then** task two describes the dependent task that must be completed one after the other.

- **When** task two is finished, start two tasks; Task 3 **and** Task 4 describe multiple successor tasks that can both start as soon as Task 2 is completed.

- **When** task 5 **and** 6 are done, start task 7. It is a multiple predecessor test because it can't start until two or more previous tasks are completed.

 ## Working with Complex Task Patterns
 When several task patterns combine, the facts must be studied very carefully to understand the logic and sequence. A project schedule is only accurate if the underlying task pattern is correct. For example, consider the following three fact statements and the task patterns they represent. Examples of task patterns are shown in Figures 3-13,, 3-14, and 3-15.

1. **Dependent tasks**: Perform task 1. When task 1 is complete, perform task 2.

2. **Dependent tasks and multiple successor tasks**: Perform task 1. When Task 1 is complete, perform Task . When Task 2 is finished, start Task 3 and Task 4. When Task 3 is complete, start two more tasks: Task 5 and Task 6

3. **Dependent tasks, multiple successor tasks, and multiple predecessor tasks**: Perform task one, when task one is complete come perform task 2. When task two is finished, start task 3 and task 4. When task 3 is complete, start two more tasks.: task 5 and Task 6. One task 5 and 6 are done. Start task 7. Then when task four and 7 are finished, perform task 8. 

##### Case in Point 3.2: Parellel Services
The project management team at Parallel Services is debating how to define tasks in the WBS. The project manager wants to break tasks down into the smallest possible units. For example, they objected to a broad task statement called Develop a Training Schedule. They suggested three sub tasks. Instead they decided to. Determine availability of training room, determine the availability of attendees, and to select specific dates and training times.



 Another project team member disagrees. Saying the broader task statement is better because it allows more flexibility and produces the same results. They say that if you break tasks into pieces that are too small, you risk over managing the work and spending more time on monitoring than actually performing the tasks as a fellow team member. Which approach do you agree with more? What are the pros and cons that you have each? 

# 3.2.3 The CRITICAL PATH
Test patterns determine the order in which the tasks are performed. Once the task sequence has been defined, a project manager can schedule the tasks and calculate the critical path. A critical path is a series of tasks that, if delayed, would affect the completion dates of the overall project. If any task on the critical path falls behind schedule, the entire project will be delayed.

 For example, suppose that Joanne and Jim are invited to someone's home for dinner. Joanne arrives on time, but Jim arrives 30 minutes late. Jim's arrival is part of the critical path because the host does not want to start without him, so the meal will be served 30 minutes later than initially planned.

 Project managers must always be aware of the critical path so they can respond quickly to keep the project on track. Microsoft Project and other project management software can highlight the series of tasks that form the critical path.

 ## Calculating the Critical path
 Figure 3-16 shows a training project with five tasks. Notice that the analyst has arranged the tasks and entered the task's names IDS and durations. The task patterns should be reviewed first, in this example task 1 followed by task 2, a dependent task. Task 2 has two successors tasks: task 3 and Task 4. 3 and 4 are predecessor's tasks for task 5.

 The next step is to establish start and finish dates, which will determined the critical path for the project. The following explanation outlines a step by step process. The result is shown in Figure 3-17.

 - Task one starts on day one and last 10 days, so the finish date is day 10.

 - Task 2 which is dependent on task one can start on day 11. The day after task one ends. With a duration of 30 days, tasks two will end on day 40.

 - Tasks 3 and 4, or multiple successor tasks that can start after task two is done. Task two ends on day 40, so tasks three and four can start on day 41. Task three last five days and will end on day 45. Task for last 25 days and will end up on day 65.

 - Task 5 depends on task 3 and 4, which are multiple predecessors. Because task 5 depends on both tasks, it cannot start until the later of the two tasks is complete. In this example, task 3 ends earlier, but task 4 will not be completed until day 65. So task 5 cannot start until day 66, (`making it the critical path?`).

 Recall that the critical path is a series of tasks of that if delayed, would affect the completion dates of the overall project. In this example task I and two are the first tasks on the critical path. Now look at task 5. Which cannot start until task 3 and 4 are done. In this case task 4 is the controlling factor because task four finishes on day 65, 20 days later than when task three finishes on day 45. Therefore, the start date for task five is determined by the finish date from task 4.

 In contrast, task three has slag time and could be delayed up to 20 days without affecting task five. Slack time is the amount of time that the task could be late without pushing back the completion date of the entire project. Task 124 and five represent the critical path highlighted with Red Arrows in Figure 3-17.
 

# 3.3 People Management
Technical prowess is highly priced in the dynamic world of system analysis and design. However, success in this field is more than just about understanding and applying complex methodologies or navigating sophisticated software. For example, one of the most critical skills involves something other than code or systems: people management. Indeed, it is a complementary skill vital for a project success.
 
 People are the most valuable asset in any industry, and system projects are no exception. Effective people management can make or break a project, Whether managing software developers, data analyst, user experience (UX) designers, or stakeholders. The ability to empathize with users, manage team dynamics, foster growth, handle change, and build trust can significantly impact the success of a project. It enhances teen morale, improves user satisfaction and ultimately leads to better, more effective systems.

 For students aspiring to enter this field, developing people management skills alongside other technical abilities can help them become well rounded professionals capable of leading successful systems projects in the future.

# 3.3.1 Understanding the human element
Every project begins and ends with people. Before the first line of code is written, people identify a problem and conceptualize a solution. Then, once the system is operational, it is used by people who benefit from its functionalities and face its limitations. For instance, an analyst designing an online banking system should understand the user's proficiency level with digital platforms, their concerns regarding security, and their expectations of convenience and efficiency. This human focused approach can mean the difference between a well received system and one that frustrates users.

 This fundamental human element underscores the importance of effective communication (described in more detail below) A proficient systems analyst must communicate complex ideas clearly and concisely, translate technical jargon into lay terms for stakeholders, and accurately grasp and address users needs. Empathy, active listening and patience becomes as vital as technical expertise.

 # 3.3.2 Team dynamics in collaboration.

 People management and system analysis and design also involves navigating team dynamics. Diverse teams can provide a wealth of ideas and perspectives leading to innovative solutions. Analysts with solid people management skills can harness the diversity of innovation and problem solving. However, it can also lead to conflicts. A good team leader must ensure that all voices are heard and that disagreements are handled constructively.

 For example, in the project aiming to develop an E commerce platform a systems analysts might need to facilitate discussions between UX / UI designers prioritizing user experience, and database administrators concerned about data integrity and security. Balancing these different perspectives and fostering a spirit of collaboration can lead to a more effective, comprehensive design. 

 Moreover. Fostering effective collaboration is critical given the multidisciplinary nature of systems projects. This involves building a conductive environment that encourages open communication, shared responsibility and mutual respect among team members.

 # 3.3.3 Nurturing growth
 Part of people management also involves fostering growth. Nurturing growth in a team is about creating opportunities for learning and development. The system analysis and design field constantly evolves in keeping the team skills current is crucial. This might involve providing training opportunity, encouraging attendance at industry events, or allocating time for self learning and exploration.

 For instance, if a company transitions from a relational database management system to a no SQL database, a manager might organize training sessions for the team, allocate time to familiarize themselves with the new system, or even invite industry experts for a workshop.

 Another aspect of nurturing growth is fostering a culture of feedback and continuous improvement. Regularly reviewing performance, acknowledging good work and providing constructive criticism can help team members refine their skills and grow as professionals.

 # 3.3.4 Dealing with Change
 Change is the only constant in a technical industry like systems analysis and design. Systems projects. Often bring about significant changes in processes, technology and job rules. Such changes can be stressful for the people involved. Managing these changes effectively requires empathy, flexibility and good communication skills.

 For example, when a company implements a new enterprise resource planning (ERP) system, It's not just about setting up the system, but also ensuring the employees are prepared for the change. This could involve organizing training sessions, being open to employees concerns and questions, addressing any resistance or fear, and reassuring them of the role and importance within the change scenario.

 Effective people management means recognizing the disruptive nature of change and providing support during transitions. This can involve clearly communicating what the change entails and why it's necessary, addressing concerns and providing training or resources to help people adapt.

 # 3.3.5 The Role of Trust
 Truss is a fundamental aspect of effective people management. When people feel trusted, they tend to be more committed, more willing to take on challenges, and more likely to feel a sense of ownership over their work. But building trust within a team isn't an overnight job. It takes time, consistency and fairness. As a system analyst or manager, your team needs to trust your decisions and your ability to guide the project to successful completion. In the context of systems projects, trust can take several forms. For example, trust in a team member's technical skills, decision making abilities, or understanding of user needs. Cultivating this trust requires consistency, reliability, and open, honest communication. For example, consider implementing a complex project like developing an Artificial intelligence (AI) driven customer service system. The project would require the team to work with unfamiliar technology and might involve a higher risk of failure. Trust in the project leader's competence and decision making ability can ensure the team's commitment and cooperation, even in the face of challenges and uncertainty.

# 3.4 Communication Management
Effective communication is a critical aspect of systems projects. However, it can often pose significant challenges. Communication related issues in this context include miscommunication of requirements, lack of regular project updates, ineffective change, communication, cultural and language barriers, and dealing with problems. More details on tools and techniques that support the communication aspects of managing systems projects are provided in Appendix A.

# 3.4.1 Miscommunication of requirements.
Miscommunication or misprepensation of system requirements is a common issue that can significantly impact the effectiveness of systems projects. Clear, accurate communication of requirements from the stake holders to the project team is the foundation for the entire project. However, when requirements are miscommunicated, it often leads to a product that fails to meet user needs or expectations, causing dissatisfaction and necessitating costly and time consuming rework. As detailed later in the book, one of the main reasons for the miscommunication of requirements is the difficulty in translating business needs into technical requirements. Stakeholders might need a clear understanding of what they need to struggle to articulate their needs in a way the project team can understand. Similarly, the project team, especially those with a more technical focus, may not fully grasp the business implication of specific requirements, leading to misunderstandings. To address this issue, it's vital to facilitate open, clear and regular communication between all parties. This can be done through workshops, interviews or regular meetings with stakeholders, and project teams can discuss requirements in detail. Case scenarios, user stories, or prototype demonstrations can help clarify requirements. Furthermore, employing a business analyst with technical and business acumen can help bridge the gap between stakeholders and the project team.

# 3.4.2 Lack of regular project updates.
Regular communication about the project status is essential to keep all team members and stakeholders informed. It ensures all stakeholders are aligned, fosters a sense of involvement, and prevents surprises or misunderstandings about the project's progress. Project updates can be communicated via Project Reports, Status Meetings, and Status Reports.

 When project updates are a regular or nonexistent, it can lead to confusion and misaligned expectations, often resulting in delays or conflicts. This could occur if project managers do not communicate consistently, if there are too many communication channels causing information to get lost, or if team members are not proactive in sharing updates. Team members might assume that everyone knows what they're working on, or might be too engrossed in their task to provide updates. This can lead to a lack of understanding of the bigger picture in the project's overall progress. Addressing this challenge requires establishing explicit communication norms and expectations. This might involve setting up regular team meetings, creating project dashboards for real time updates, or using project management tools to track tasks and progress. It's also essential to foster a culture where communication is valued and encouraged, team members feel comfortable sharing updates, asking questions and discussing issues.

 ## Project Reporting
 Project team members regularly report their progress to the project manager, who in turn reports to management and users. The project manager collects, verifies organizers and evaluates the information received from the team. Then the manager decides which information needs to be passed along, prepares a summary that can be understood easily, adds comments and explanations if required, and submitted to the management and users.

 ## Project Status Meetings
 Project managers like the ones shown in Figure 318, schedule regular meetings to update the team and discuss project status, issues, problems, and opportunities. Although meetings can be time consuming, most project managers believe they are worthwhile. The sessions allow team members to share information, discuss common problems and explain new techniques. The meetings also enable the project manager to seek input and conduct brainstorming sessions.

 ## Project Status Reports
 A project manager must report regularly to an immediate supervisor, upper management, and users. Although we progress report might be giving verbally to a direct supervisor, reports to management and users are usually written. Gantt charts are often included in progress reports to show project status graphically.

 # 3.4.3 Ineffective change communication.

 Systems projects often involve changes, changes in requirements, design, project scope and so on. If these changes are not effectively communicated to all concerned parties, it can lead to confusion, errors and delays. For example, if a change in system design is not adequately communicated to the development team, they may continue working based on the old design, wasting time and resources. Ineffective change communication often stems from a need for clear change management procedures. For example, changes might be discussed in an ad-hoc manner, or information might only reach some of the members, leading with inconsistencies. Additionally, the impact of changes might not be adequately communicated, leading to a lack of understanding of the changes significance. Addressing these communication issues involves creating clear communication protocols, implementing robust change management procedures, utilizing effective communication tools, and fostering an open and transparent communication culture within the project team. In addition, all changes should be documented and the relevant party should be informally, promptly. It may also be helpful to hold meetings or workshops to discuss significant changes, ensuring everyone understands them and their implications. Lastly, fostering a culture that embraces change rather than fearing it, can encourage team members to stay adaptable and responsive to changes, leading to smoother project execution.

 # Cultural and language barriers
 In today's globalized world, systems, projects often involve diverse or geographically distributed teams. While this diversity can bring a wider range of perspectives and skills to the project, it can also lead to communication issues due to cultural or language barriers. For example, team members from different cultural backgrounds may have different communication cells or interpretations of messages. Similarly, team members speaking other primary languages can lead to misunderstandings or misinterpretations. For example, direct communication may be the norm in one culture, while a more indirect, nuanced approach is preferred in another. Misunderstandings can arise if if these differences are not understood and respected. Similarly, if the project's called working language differs from a team members first language, they might need help expressing their thoughts accurately or might need clarification on information. Addressing this challenge requires building a culture of understanding, respect and patience within the team. Team members should be mindful of potential cultural and language barriers and seek clarification when in doubt. Tools like translation apps or multilingual team members can assist in overcoming language barriers. Additionally, training in intercultural communication can help team members understand and navigate cultural differences more accurately.

 # 3.4.5 Dealing with Problems
 Deciding how to communicate potential problems can take time and effort. At what point should management be informed about the possibility of cost overruns, scheduled delays, or technical problems? At one extreme is the overly cautious project manager who alerts management to every potential snag and slight delay. The danger here is that the manager loses credibility overtime and management might ignore potential serious situations. At the other extreme is the project manager who tries to handle all situations single handedly and only alerts management once problems is serious. By the time management learns of the problem, little time might remain to react or devise a solution. A project manager's best course of action lies between the two extremes, but is probably closer to the 1st. If the consequences are unclear, the analysts should err On the side of caution and warn management about the possibility of a problem. When the situation is reported, what is being done to handle and monitor the problem should be explained. If the situation is beyond the analysts control, possible actions management can take to resolve the situation should be suggested. Most managers recognize that problems occur on most projects; It is better to alert management sooner rather than later.





# 3.5 Technology Management
Technology Management for Systems projects refers to the strategic selection, implementation, and review of the technology resources used throughout the SDLC. It's a crucial aspect of ensuring that the systems developed are efficient, reliable and capable of meeting the organization's current and future needs. Effective technology management starts with choosing the right technology tools. In systems projects, this can include software for modeling and diagramming, project management tools, platforms for collaboration and communication, testing tools, and more. The selection process should consider factors such as the functionality and scalability of the tools, their compatibility with existing tachnology infrastructure, the learning curve for the team, and the costs. However, technology management continues beyond selection and acquisition. Once the tools are in place, they must be properly maintained to ensure their ongoing performance and reliability. This involves regular software updates, troubleshooting, security checks, and system backups. Moreover, as business needs and technology landscapes evolve, the Technology Strategy must be regularly reviewed and updated. This could mean phasing out outdated tools, adopting new ones, or upgrading existing systems. This continues attention to technology management is key to ensuring systems analysis and design process remains efficient and effective, delivering high quality results that drive the organization's success.

## 3.5.1 Technology Selection
Selecting the right technology tools is a critical part of effective technology management. Several software tools are available in systems projects, from modeling to testing. The choice depends on various factors, including the scoping, nature of the project, the team's familiarity with the tools and the tools' alignment with the project's goals.
Functionality is a key criterion, meaning the tools must possess the features required to carry out the intended tasks. Scalability is another important consideration, particularly for large projects or those expected to grow over time. In addition, the tools must handle increased data volume or complexity without performance degredation. Also, compatibility with existing technology infrastructure is essential to ensure seamless integration and avoid disruptions. Finally, cost effectiveness should be evaluated. This includes the purchase price or subscription fee and factors like training cost, maintenance expenses, and potential costs associated with downtime or tool related issues.

# 3.5.2 Technology implementation.
Once suitable tools are selected, the implementation phase begins. This involves requiring the software, installing it, integrating it with existing systems, and configuring it to meet project requirements. It also includes training and projecting to use tools effectively. Effective implementation is not just about technical setup. It also involves managing change within the team and the broader organization. This can mean addressing resistance, prompting buy in, and ensuring that everyone understands the new tools's benefits and how to use them. Moreover, it's important to manage expectations during the implementation phase. Not all benefits will be immediate and challenges or teething problems may exist. Therefore, patients regular communication and responsiveness to feedback and issues are essential during the transitional. Technology implementation related to product development and system support strategies is covered in more detail later in the book.

# 3.5.3 Technology Review.
 Even the best tools require ongoing maintenance to perform optimally. Regular software updates must be installed to benefit from new features, improvements, or bug fixes. In addition, regular checks should be made for any issues or irregularities, and prompt troubleshooting should be carried out to minimize downtime. Security is another critical aspect of technology maintenance, particularly giving the sensitive data often involved in systems and analysis and design. Therefore, regular security checks and updates, strong access controls and proactive measures against potential threats are essential. Lastly, continue his review of technology tools as necessary as the business environment and technology landscape evolve. Once effective, tools might become outdated or less efficient, or better options might become available. Regularly reassessing the Technology Strategy and adjusting as needed helps ensure that the system analysis and design process remains effective and agile, ready to deliver high quality results in a constantly changing world. Technology will be related to system security and support strategies is covered in more detail later in the book.



 # 3.6 Financial Managegment
 Sound financial management is crucial, often overlooked aspect of a successful systems project. Understanding the economic implications of system projects can profoundly impact project outcomes and the overall efficiency of the business operation. The most critical areas of concern include budgets and cost estimation, skills and technology investment and return on investment analysis. More details on financial analysis tools and techniques that support the financial aspects of managing systems projects are provided in Appendix B.

 ## 3.6.1 Budget and Cost Estimation
 Every project begins with a vision and a budget. Leaders and practitioners need to assess the financial viability of a project before embarking on it. Detailed cost estimation and budgeting are pivotal to this assessment. Factors to consider may include `labor costs`, `software and hardware expense`,` training requirements`, `maintenance cost`, and `potential cost overruns`. Proper cost estimation at the beginning can set the stage for a project's financial health and prevent unexpected monetary issues later in the SDLC. Once the budget is set, `the challenge lies in efficienctly allocating your resources`. This process requires balancing the dual goals of meeting project needs and _staying within budget constraints_. The resource allocation plan should consider the `most critical aspects` of the project and assign resources accordingly. It should `also factor in potential risks and have contingency provisions`.

# 3.6.2 Skills and Technology Investment
Investing in skills and technology is critical in the financial management aspect of system projects. With technology evolving, at breakneck speed organizations must ensure their` teams are equipped with the latest tools and possess the required skills` to use them effectively. While these investments may initially seem like additional cost, they often lead to long term financial benefits by increasing efficiency and reducing time to market. As such, investing in the right technology and nurturing the talent to maximize its potential is not just an expenditure, but an investment in the organization's future.

Investing in technology includes:
1. `_procuring` the latest software for design and analysis_
2. `_upgrading` hardware to support new applications_
3. `_maintaining` a robust technological infrastructure to facilitate seamless work processes_. 

For instance, investing in tools that enable agile methodologies or adopting advanced technologies like AI or **machine learning(ML)** could improve significant competitive edge. However, the choice of technology investments must align with the organization's needs, capacity and strategic goals to ensure it brings real value and does not become a cost burden.

In parallel, `investments in skills` is A corner store of maximizing the benefits of technology investments. It entails continuous learning opportunities for team members to acquire _new skills, update existing ones, and keep pace with industry trends._ This could involve structured `training programs`, `workshops`, `seminars` or even encouraging `self paced online learning`. Equally important is cultivating a culture that values and rewards knowledge sharing. As team gain proficiency in latest methodologies, tools and best practices, they enhance their competencies and boost the organization's overall capability to deliver high quality, efficient system designs.

# 3.6.3 Return on Investment Analysis
Leaders should weigh the projected benefits of the proposed system against the projected cost. A practical return on investment analysis `clarifies the new system's value to the organization`. Benefits could be `tangible`, like cost savings from increased efficiency, or `intangible`, like _improved customer satisfaction or employee morale_. Leaders should prioritize projects with a high ROI, indicating that the benefits outweigh the cost.

 In systems projects, financial management is not just about tracking dollars and cents, but `understanding their strategic implications`. Therefore, leaders and practitioners must consider the financial dimensions of their work, from _initial cost estimation_ and _budgeting_ to ongoing _monitoring and controlling expenditure_, _resources allocation_. and _risk management_. By doing so, they can ensure that their `projects are technically sound and financially viable, maximizing value for the organization.`

 Every project carries `potential financial risks`, such as _cost overruns_, _unexpected expenses_, or the _new system failing_ to deliver the expected ROI. Regular financial risk assessments enable leaders to identify and mitigate these risks `before they become unmanageable.` This could involve having _contingency funds_, _diversifying investment_s or _securing comprehensive insurance_. Managing financial risk is part of the project's overall risk management and mitigation strategy. 




# 3.7 Risk Management
Every systems project involves risks that systems analyst and project managers must address. Therefore, risk management is crucial in systems projects as it helps identify, assess and manage potential threats that could hinder project success. A **risk** is the possibility of an adverse event that could negetively affect the project. **Risk management** is a fundamental aspect of managing systems projects, as it helps` identify, assess, and prioritize uncertanties` that could impact achievement of project objectives. 

## 3.7.1 The importance of Risk Management
The importance of risk management lies in its potential to mitigate the adverse impact of uncertainties across the SDLC. Risk management is `essential` for _reducing uncertainty, improving project planning and control, enhancing stakeholder confidence, mitigating potential losses, and facilitating decision making_.

 Fortunately, a wide variety of risk management software is available to help a project manager with these tasks. For example, most packages allowable project manager to assign `specific dates as constraints`, `align task dependencies`, `note external factors that might affect the task`, `track progress and display tasks that are behind schedule`. Armed with this information, the IT team can quantify the project's risks. Just as they use financial analysis tools to quantify cost and benefits.

 Ultimately, effective risk management enhances the likelihood of project success. By proactively managing potential threats, the project is more likely to be _delivered on time, within budget and to the required quality standards_. Thus, risk management is not just about preventing negative outcomes, but `enabling positive ones.`

### Reducing Uncertainty
Systems projects often involve _using_ advanced or emerging technologies, _complex integration_ with existing systems, and _meeting evolving user requirements_. `These factors introduce considerable uncertainty` to the project. Effective risk management allows these uncertainties to be identified, analyzed and managed proactively, reducing the potential for unpleasant surprises during the project.

### Improving Uncertainty
By identifying potential risk early in the project life cycle. Risk management helps inform project planning decisions. It can `guide the allocation of resources`, the `scheduling of tasks` and the `setting of project milestones`. Furthermore, the _continual monitoring_ and _controlling_ of risk help keep the project on track, detecting deviations from the plan early and facilitating timely corrective actions.

### Enhancing Stakeholder Confidence
Stakeholders, including clients, team members and upper management, must have confidence in the projects ability to achieve its objectives. `A commitment to due diligence and proactive problem solving is demonstrated by systematically managing systems`, thereby boosting stakeholder confidence.

### Mitigating Potential Risks
 Some risks if realized, Can lead to `substantial financial losses, delays, or even the total failure` of the project. Risk management helps to prevent these outcomes by identifying potential threats and putting measures to place to avoid or mitigate them.

### Facilitating Decision Making
 Risk management provides valuable information that aids in decision making. `By understanding the potential risk and their impacts`, project managers can make more _informed decisions_, balancing the potential benefits of an action against its associated risks.


## 3.7.2 The Origin of Risks
Risks could arise from a myriad of resources, such as `technological complexities` involving `stakeholder requirements`, `team dynamics`, `external environmental factors`, and `inherent system complexity`. The importance of risk management lies in its _potential to mitigate_ the adverse impact of these uncertainties, thereby improving the chances of project success.

It's crucial to note that these sources of `risk can interact` with each other with `1 risk potentially triggering risks in another area`. For instance, a change in requirements (stakeholder needs) could lead to technical challenges. Or technological complexities, which in turn could lead to project delays (Project Management). Understanding the origins of these risks can significantly aid in their early identification and successful management.

### Technological complexities.

One `significant` source of risk stems from the `technological complexities`. With this rapid pace of technological innovation, system projects frequently involve using new (unproven technologies). As a result, there may be `uncertainties about the technical feasibility` of the project or `the performance and reliability` of these technologies. Additionally, risk can arise from _software or hardware failures, security vulnerabilities, or data management issues_.

### Evolving requirements.

Changes in requirements are another significant origin of risk in system projects. `Stakeholders may alter their needs and expectations` during the project, `leading to a project scope, timeline, or budget changes`. This can introduce `significant uncertainties` into the project and `may require rework, leading to increased costs and delays`. Furthermore, _discrepancies or misunderstandings in interpreting the requirements may lead to misalignment_ between the designed system and the stakeholder needs.

## Team Dynamics

The project team and management practices can also be a resource of risk. This can include risks related to team dynamics such as `conflicts`, `lack of cohesion` or `inadequate communication`. In addition, there may be risk associated with project management, such as inadequate planning, poor risk management or ineffective leadership. `Human errors` during requirement elicitation, system design, coding, testing, or deployments can also lead to significant issues.
 New. New.


## External factors.

 The external environment can also give rise to risks. This includes changes in `market trends, regulatory changes, or shifts in economic conditions`. For instance, new regulations may require changes to the data's management practices, or an economy downturn may affect the project `budget`. 

## Size and Complexity

Lastly, the `inherent complexity and size` of the system can be a risk factor. larger and more conplex projects have mote elements that could wrong, leading to increased uncertainties. Additionally, the interdependencies between parts of the system mean that an issue in one area can have a `ripple effect`, leading to problems in other areas. 

# 3.7.3 Risk Management Tasks
Although project management experts might have differing views about the number of steps or phases needed. A basic list of risk management tasks would `include: a risk identification analysis and respond planning.` This task from the core of risk management and systems projects serving as essential components for the successful completion of any project. Their importance is underscored by the by the role in reducing project uncertainties, promoting informed decisions, and maximizing project success. **`(I did not understand this secction at all. How is having defferent views over how many step a RISK?)`**

## Risk Identification
**Risk identification** is the `first and arguably the most crucial` step in the risk management process, and involves systematically identifying possible threats or certainties that could hamper the success of the system's analysis and design project. `A detailed understanding of the project, its contextt requirements and the technology involved, is imperative` to identify potential risks. This stage forms the foundation of the risk management process because identifying potential risks is necessary to ensure further steps can be taken towards managing them.
.
 The process of **risk identificatio** can be conducted using various techniques, some which could include brainstorming sessions with project stakeholders. The **`Delphi technique`**, in which experts anonymously contribute their opinions;` SWOT analysis` to examine `strengths, weaknesses, opportunities, and threats; and risk breakdown structures`, which _offer a hierarchical decomposition of risks_. Other techniques can also be used, such as `interviewing stakeholders`, r`oot cause analysis` or `reviewing historical data and lessons from similar past projects`. To compile a comprehensive list of possible risks that may arise during the project's life cycle.

  The result of risk identification is usually a `risk register`. Which is `a document detailing all the identified risks along with their characteristics.`This register forms a key input to the subsequent risk analysis stage. However, it's essential to remember that risk identification is `NOT a one time process`, but a continual activity throughout the project. New risks may emerge and older ones may become irrelevant as the project progresses. Hence the need for regular reassessment and updating of the risk register.

## Risk Analysis
**Risk analysis** is the `second stage` in the risk management process following the identification of potential risks. This stage `involves assessing the identified risks based on their likelihood of occurrence and the severity` of their impact should be materialized. Risk. Analysis aims to prioritize risks and _help project managers understand the risks and potential influence on the project_. This `helps in decision making` regarding the `allocation of resources` and the `focus of risk management efforts`.

**Quantitative risk** analysis seeks to `assign numerical values to risks`, estimating their potential impact on the project objectives in terms of `dollars`, `time`, `project scope`, or `quality`. This could involve techniques such as `sensitivity analysis, decision tree analysis, or Monte Carlo simulations`. It can also involve a modeling process called `What if analysis`, _which allows a project manager to vary one or more elements in a model to measure the effect on other elements_. This topic is discussed in more detail later in the book.

The output of the risk analysis activity forms a `crucial input to the risk response planning stage`. As with a risk identification, risk analysis is `NOT a one time activity`, but should be periodically revisited as a project progresses. Changes in project parameters, environment or stakeholder inputs can change the risk landscape, hence the need for regular updates and assessments.

## Risk Response
Creating a **risk response plan**. The next stage in risk management. _After identifying_ and _analyzing risks_, the focus turns towards deciding `how to address each`. Each identified and analyzed risk requires a suitable response strategy. Chosen `based on the nature and severity` of the risk, this stage `aims to minimize` the potential impact of risks on the projects objectives.

 There are typically `four risk responses strategies: avoidance, transfer, mitigation, and acceptance`. 

 - **Risk avoidance** involves `changing the project plan` to eliminate the risk or protect the project objectives from its impact. 

 - **Risk transfer** `shifts the effects of the risk to a 3rd party`, typically through insurance or outsourcing. 

 - **Risk mitigation** seeks to `reduce the probability or impact` of the risks to an acceptable level. 

 - **risk acceptance** involves acknowledging the risk and making a `deliberate decision to accept it` without engaging in special efforts to control it.

 Regardless of the chosen strategy, each response must be assigned to a responsible individual, the `risk owner`, who_ monitors and manages the risk_. Additionally, the `chosen responses form the basis for the risk management plan`, a critical component of the overall project management plan. Like the previous steps, risk response planning is an `ongoing process that should be revisited` regularly as the project progresses. As of now, the first three stages of risk management is a continuous, not a one time task.

# 3.7.4 The Risk Management Plan
The risk management plan is a summary of the risk identification, risk analysis and risk response activities. It can include a review of the project's scope, stakeholders, budget, schedule, and any other internal or external factors that might affect the project. The risk management plan should address three additional areas.: monitoring and control, roles and responsibilities, and risk communication.
The risk management plan should be reviewed and updated regularly, particularly when significant project changes occur. It serves as a road map for managing risks and helps ensure that everyone involved in the project understands how risks are to be dealt with.
 New. New.


 ## Monitoring and Control
 This component of the risk management plan is `crucial` as it outlines 
 - `How the project team will keep track of the identified risks`
 - `Monitor residual tasks`
 - `Identify new risks that may arise`
 - `Ensure that risk responses are implemented effectively` throughout the SDLC. 
 
 These procedures aim to ensure that risks are continually reassessed and managed throughout the project life cycle, thereby minimizing their impacts on the project's objectives.

 This `process is iterative and dynamic`, as risks and their `impacts and likelihood can change` throughout the project. There could be` triggers or signs` that a risk event is about to occur, or` new risks may be introduced` due to changes in _project scope, timeline, technology or other factors_. Hence, having a well defined procedure for monitoring and controlling risks is vital.

 The plan could `outline specific risk indicators` to watch for regular risk review meetings or specific risk monitoring tools to be used. It could include: 
 - `Updating` and revising the risk register 
 - `Tracking` metrics 
 - `Reassessing` existing risks 
 - `Conducting` audits 
 - Keeping stakeholders `informed` about the status of risks.


 On the `control` side, it involves 
 - `Executing` the planned risks response strategies when necessary 
 - `Reassessing` the effectiveness of the strategies
 - `Modifying` them if they are not working as expected. 
 - It could also involve `taking corrective action` if the project veers off track due to realized risks. 
 
 This section of the plan `also defines the frequency of review and update cycles.` For some projects this could be a `weekly` activity, while for others it might be `less frequent`. Again, this largely depends on the nature of the complexity of the project and the volatility of the project environment.

 ## Roles and Responsibilities
 This part of the risk management plan delineates the `specific duties of each team member` concerning risk management. It defines who will 
 - `identify`
 - `analyze`
 - `manage risks`
- `ensure a clear chain of responsibility`. 

 This could range from the person in charge of the overall risk management process, `often the project manager`, to the individuals responsible for specific tasks such as _risk identification analysis and response implementation_.

 Some projects may designate risk owners who are responsible for specific identified risks by explicitly stating who was responsible for what. The plenures that risk management tasks are performed efficiently and that there's a clear accountability for each risk. This eliminates confusion about who should act when a risk event occurs and ensures that risks are not overlooked because everyone thought someone else was handling them.

 ## Risk Communication
 Effective risk communication. It is `crucial` to successful risk management. This part of the plan describes `how risks and risk management activities will be communicated to stakeholders.` This might include the `methods` of communication(Email updates, project meetings, risk reports), the `frequency` of communication(Daily, weekly. Monthly), and the stakeholders who should receive the communication.

 It also indicates `what kind of information should be communicated`, such as changes in _project risks, results of risk analyses and progress in implementing risk responses_. The goal of the risk communication plan is to ensure that `everyone involved in the project has the necessary information to make informed decisions` and that there are no surprises when risk events occur. 


# 3.7.5 Risk Managrmrnt Issues
**Risk management** in system projects is often challenging due to their `inherent complexities` and `uncertainties`. Some _common risk_ management issues in such projects include: 
- `inadequate risk identification`
- ` poor risk assessment`
- `ineffective risk responses`. 

Addressing these issues requires a `systematic, proactive` approach to risk management.


With a `commitment` from all stakeholders, `effective communication` continues monitoring and `updating of risks` and a `culture` that values and understands the importance of risk management.

 ## Inadequate Risk Identification
 One of the biggest challenges of risk management is identifying all potential risks. `Due to the complexity` of system projects, unknown risks may only become apparent as the project progresses. Some project teams might not `invest sufficient time identifying potential risks` or l`ack the necessary expertise` to foresee potential threats. This could result in a _critical risks going unnoticed_ until they become actual issues! Inadequate risk identification can lead to `unpleasant surprises and unfortunate disruptions` in the project.

 ## Poor risk assessments.

 Even when risks are identified, `assessing their potential impact and likelihood can be challenging`. If risks are not adequately evaluated, the team `might underestimate` the potential damage `or overcommit resources` to less significant threats. `In addition, there may be a lack of objective criteria(what does this mean? a lack of what?)` for evaluating risks, leading to _subjective or inaccurate_ risk assessments. Similarly, a risk assessment based on `incorrect` or `outdated information` could lead to misguided decisions and strategies.

 ## Ineffective Risk Responses
 Once risks are identified and assessed, developing mitigation strategies is next. However, these strategies can often be `ineffective` or `misaligned` with the risk's nature without clear `procedures or guidelines`. This could be due to: 
 - lack of resources
 - lack of commitment
 - inadequate planning 

    Or 

 - the risk management process might be reactive rather than proactive (addressing risks only after they've occurred). 
    
    For instance, a team might rely on a _generic response_ strategy for all identified risks, rather than tailoring their approach `based on the specific risk characteristics`. Ineffective risk responses `can increase project cost and delays.`



# 3.8 Porject Management Software
Project management `software plays a crucial role` in the execution and control of system projects. These projects often involve many tasks, diverse teams, numerous deadlines, and resources requiring careful orchestration. The software provides a comprehensive platform for managing these different components: 
- `helping to plan`
- `execute`
- `monitor`
- `control all project activities`.

 Additionally, these tools promote: 
 - `real time collaboration`
 - `document sharing`
 - `communication among diverse stakeholders `
    
    Including _system analyst, developers, testers_ and _end-users_, facilitating an effective and cohesive project environments. 

One of the key benefits of project management software is the `enhanced efficiency` it brings to the project. The software streamlines operations by automating several project management tasks like _scheduling_, _resource allocation_ and _progress tracking_, `saving time and effort`. This let's project managers concentrate on higher value activities. Furthermore. These tools often incorporate _risk management features_, which are vital for `identifying`, `analyzing` and `controlling potential project risks`, thus decreasing the likelihood of project disruptions or failures.

Project management software also promotes `transparency and accountability` by providing visibility into project _progress_, _resource utilization_, and _task completion_. This clarity `fosters a sense of responsibility`, as each team member can see who is accountable for each task and whether it has been completed as scheduled. In addition. `Supports informed decision` making by offering up to date, accurate data on project status and performance. Lastly, the software `serves as a repository for project documentation, historical data and lessons learned`, which is beneficial for knowledge management and future project planning. Integrating with other tools used in system projects further enhances the utility of project management software, allowing for seamless workflow and reliable data across different tools. 

# 3.8.1 Aread of Support
Project managers use software applications providing an array of features that assist in areas such as: 
- `planning and scheduling`
- `resource management`
- `communication and collaboration`
- `documentation and knowledge management`
- `risk management`
- `monitoring and control`
- `tool integration. `

By providing these capabilities, project Management software can significantly 
- enhance the `efficiency and effectiveness` of systems projects.
- `reduce` project risks
- improve `team collaboration`
- ensure project objectives` are met on time and within budget`
- `increase` the likelihood of project success.

It is important to note that many modern project management tools are quite versatile and combine features from multiple categories. For instance, tools like jira, monday.com, and Zoho projects provide comprehensive functionalities that span task management, resources management, and portfolio management`(What does it mean by a portfolio management?)`.

 ## Planning and Scheduling
 Complex systems projects often involve numerous independent tasks and milestones that must be carefully scheduled. Project management support provides tools like `Gantt charts` and `critical path analysis` that help create detailed _project schedules, identify dependencies between tasks, and visualize the project timeline_. This helps in setting `realistic timelines` and `monitoring progress` against the plan.

 ## Resource Management
 Resource management in systems projects, facilitated by project management software involves `effectively allocating and tracking organizational resources`, _including human resources and tangible assets_. The software ensures: 
 - `Optimal utilization` of resources and balancing workloads
 - `Monitoring costs`
 - `Maintaining` the project within its budget. 
 
 Effective resource management helps to ensure that projects are completed `on time` and `within predefined objectives. `

 ## Communication and Collaboration
 Communication and collaboration are `key` in systems projects, and project management software enhances these aspects by providing platforms for `real-time interaction, file sharing and cooperative work`. Such tools breakdown silos and allow diverse project stakeholders, including s_ystems analysts, developers and testers to communicate and cooperate effectively_. The result is a `well coordinated project team` working seamlessly towards shared project goals. 

 ## Documentation and Knowledge Manegement
 Documentation in systems projects is crucial and the project management software `acts as a centralized repository for all project related documents`, from _system specifications to user manuals_. This centralized storage allows team members `easy access `to the information they need. Reducing time spent searching for documents and enhancing overall project efficiency. Furthermore, this documentation is a `historical record`, _invaluable_ for future project planning and knowledge management. 

 ## Risk Management
 Many project management software solutions include tools for `identifying`, `tracking`, and `merging risks`. These could include: 
 - Risk registers
 - Risk analysis tools
 - Dashboards that visually overview the projects risk status. 
 
    These tools can support the risk management process by making it easier to record, update, and communicate about risks.

 ## Monitoring and COntrol

 Project management software provides various tools for `monitoring project progress` and `controlling deviations` from the plan. These could include: 
 - `Dashboards` that display key performing indicators
 - `Reporting tools` that generate detailed progress reports
 - `Alert systems` that notify the project manager when tasks are running late or resources are overallocated.

 ## Tool Integreation 
 A key advantage of project management software in systems projects is its ability to _integrate with other software tools the team might use_. This can include integrations with `coding and design tools`, `version control systems`, `testing tools`, `customer relationship management systems`, and more. This interoperability helps: 
 - Streamline workflows
 - Minimize manual data transfer
 - Ensure consistency and accuracy of information across different tools.

    For instance, some project management software can integrate with tools like Microsoft's Github, allowing you to `track code commits` and `link them directly to specific tasks in your project plan`. 
    
    Similarly, integration with a tool like JIRA can help track and `manage your bugs and issues` directly within the project management software. 
    
    This high level of integration `increases efficiency` and `enhances visibility` across the project, enabling team members and stakeholders to have a comprehensive and unified view of the project status. In addition, it ensures `everyone can access the most recent and accurate` project information, leading to better decision making and improve project outcomes. 


# 3.8.2 Examples of Project Management Software
Project management software is pivotal in `planning`, `executing` and `controlling` various projects. They enable project leaders and team members to: 
- Track tasks
- Collaborate
- Manage resources
- Analyze project performance. 

Project management software includes tools and apps for: 
- Collaboration
- Document management
- Issue and bug tracking
- Project portfolio management
- Resource management
- Task management
- time tracking. 

The website for these tools have more information about their capabilities, including demos, trial versions, and training material.

 ## Collaboration
 Collaboration software helps teams `communicate and collaborate effectively`, especially when team members work remotely or across different locations. These tools provided features like; 
 - file sharing
 - real time editing
 - common threads
 - integrated messaging systems. 
 
As a result, they aid in `reducing communication bottlenecks` and `facilitate efficient collaboration` among team members. Examples include Slag, Microsoft Teams, and Google Workspace.

 ## Document Management
 These tools help teams `organize`, `manage`, and `track` documents related to the problem. Features typically include:
 - version control
 - document sharing and collaboration
 - search functionality
 - access control. 
 
    They can be especially valuable in projects with a `large volume of documentation`, or where documents must be `regularly shared and collaborated` on. Examples include _Google Docs, Microsoft Sharepoints, and Athlasian Confluence._

 ## Issues and Bug Tracking
 This type of software is crucial in software development and IT project management. It helps teams `record`, `track`, and` manage issues and bugs` that arise during the development process. These tools generally provide features like 
 - `issue logging`
 - `tracking assignments`
 - ` resolution status updates`
    
    This making it easier for teams to collaborate on fixing issues and improving product quality. Examples include JIRA, Bugzilla and Github issues.

 ## Project Porfolio Management
 **Project Portfolio Management (PPM)** software provides a `high level perspective` of all the projects in an organization's portfolio. It's a tool commonly used by project managers and executives to make `strategic decisions` offering features to:
 
 - `Align` projects with business objectives
 - `Track` their progress
 - `Manage` associates risks.

 PPM software provides a `comprehensive view of all ongoing projects`. It helps leaders understand:
 - how resources are `allocated` across the portfolio
 - how individual projects `perform`
 - how they align with the organizations `broader strategic goals. `
 
 These insights can `inform decision making`, enabling leaders to:
 - `prioritize` _projects_
 - `allocate` resources more _effectively_
 - `identify` and `mitigate` _potential risks_.

 Microsoft Project is a full featured traditional project management tool with a significant market share. It offers:
 - PERT/CPM and GANTT charts
 - Resources
 - Scheduling
 - Project calendars. 
 
    Microsoft Project is available as a software product for Windows and as an add on online service as part of selected Office 365 plans. 

 In addition to Microsoft Project, several other project management tools are available. For example, `GanttProject` is a cloud based project management tool that can:
 - automatically produce gotts charts and PERT/CPM charts
 - calculate the critical path
 - read/writes Microsoft project files. 
 
 `Gantter` is a `free`, _Cloud based_ project management tool. `Apptivo Projects` and `Smartsheet` are the other project management tools offering similar capabilities. As shown in Figure 3-25, the "monday-work management" tool is the web based project management component of the monday dot com work OS (Operating System)(I did not understand this last sentence, what?is it the same tool?). `Trello`, shown in Figure 3-26 is a product management tool from `Atlassian` tailored toward agile development. (explain this one too)

 ## Resource Management
 Resource management software is another `crucial` project management tool, useful in system projects. These tools help project managers _effectively manage and allocate resources across different tasks or projects_, such as
 - `personnel`
 - `hardware`
 - `software`
 - `budgets` 
 
 In addition, they provide: 
 - `overview of the available resources`
 - `current allocation`
 - `future availability`

 One key `benefit` of resource management software is the `ability to forecast resource needs` and` potential bottlenecks`. By visualizing resource allocation and tracking resource utilization, project managers can identify _overutilization_ and _underutilization_ of resources and adjust allocations accordingly to ensure more efficient use of resources.

 Examples of resource management software includes `Resource Guru`, known for its_ intuitive resource scheduling and time tracking_ features; `Float` a popular tool for _planning resources in agencies and studios_.; and `Smartsheet`, A versatile tool that combines_ project and resource_ management's capability.

 ## Task Management
 Task manager software is an essential tool in the world of project management, particularly when it comes to systems projects. These types of software are `primarily used to manage, track, and coordinate individual tasks within the large project`. They often provide features such:
 - to do list
 - deadlines
 - task assignments 
 
    Which help ensure that every team member knows their responsibilities and can monitor the progress of their tasks.

 Task management software can also `provide a real time updates and notifications` to keep the team on the same page. This can significantly `enhance communication` within the group as team members can: 
 - discuss tasks
 - share updates
 - resolve issues more efficiently. 
 
    By enhancing visibility and communication, task management software can `improve productivity` and `ensure` tasks are completed promptly.

 Examples of task management software include `Azana`, `Commamonday.com`, and `Trello`. For Office 365 users, `Microsoft to-do` enables seamless test management within familiar software environments for personal and work use. It allows users to manage tasks from _smart phones, tablets, browsers and computers._


## Time Tracking
This type of software allows: 
- teams to track the time spent on individual tasks or projects
- helping to ensure efficiency and productivity. 

In addition, time tracking tools can provide insights into how much time is spent on various tests, which can help with project `planning`, `resource allocation`, and `performance evaluation`. They can also facilitate `accurate client billing` for businesses that charge by the `hour`. Examples of time tracking software include Harvest. TOGGL, and TimeCamp.

# 3.8.3 using Project Management Software
The following sections explain how Microsoft Project could be used to handle the sample task summary of a preliminary investigation shown in Figure 3-29. This example illustrates that project management is dynamic and challenging. Irrespective of which project management software is used 
- A `step by step` process is followed to develop `WBS` 
- work with `text patterns`
- analyze the `critical path. `

The main difference is that the `software does most of the work automatically`. One significant advantage of this approach is that it allows the project manager to rapidly adjust: 
- `schedules`
- `estimates`
- `resource assignments to respond` to real-world events.


 ## Work BReakdown Structures
 Creating a WBS using Microsoft Project is much the same as creating it manually. _The task duration and test patterns must still be identified_. This information might have to be developed or a task summary like the one in figure 3-29 might be used. The Goal is to document all 
- `tasks`
- `dependencies`
- `dates`
- total project `durations`. 

 The `first` step is to create a GANTT chart showing the necessary information as the information for each task is entered into Microsoft Project duration and the predecessor tests, if any, should also be noted.

 ## Gantt Chart
 As tasks are entered, the program automatically performs the calculations, detect the test patterns, and create a gaunt chart. The chart consists of horizontal bars connected with arrows that indicate task dependencies. For example, tasks will not be scheduled on Saturdays and Sundays if a typical work week is selected. However, for a mission critical project, a 24 / 7 calendar might be created. Whatever is specified, the program will handle the test accordingly. Microsoft Project offers numerous `display settings, format and calculation methods`.

 ## Network Diagrams
 After the Gantt chart is completed, the data can be viewed as a Microsoft Project `Network Diagram`, which is _similar to a PERT chart_. When the network diagram option is selected, the project task's dependencies and a start and finish date for each tasks are shown. A network diagram `displays the same information as the Gantt chart`, including task dependencies, but` uses task boxes` to handle much more detail. Using Microsoft Project, each task `can be assigned to one or more people, budgets assigned, targets, progress reports produced, and schedules and deadlines` readjusted as necessary. 

## Calendar View
A `calendar view` is an excellent way to manage day-to-day activity. This view shows the tasks similar to a PERT chart `as an overlay on the actual calendar`(explain this last sentence). Because the critical path is highlighted in red, it is easy for a project manager to determine priorities at any point in time.

 Suppose the project manager wants to view the preliminary investigation in Figure 329 as a GANTT chart, a PERT chart, and a day-to-day calendar. All three views are shown in Figure 30. Each view shows the tasks, the timing, the dependencies and the critical path. You will notice that of the four tasks scheduled for September 25th, only the user survey is on the critical path. Therefore, that should be the project managers primary concern.

# 3.9 Managing Success
Managing a system project is a challenging task. It requires a balanced approach that addresses technical requirements while focusing on people and processes. Project managers` must be alert, technically competent and highly resourceful`. Successfully managing systems projects requires attention to several areas, including project `monitoring and control, managing issues as they rise, and adopting an agile mindset that acknowledges the inevitable changes that will occur as the project proceeds`. Project managers can be proud when they handle a successful project that helps the company achieve its business objectives.

# 3.9.1 Project Monitoring and Control
Project monitoring and control is a vital aspect of matching systems projects, regardless of whether the project was planned and scheduled with project management software or in some other manner. It involves the processes, tools and techniques required to keep the project on track and meet its goals and objectives. It comprises `tracking`, `reviewing` and `regulating` progress to meet the performance objectives defined in the project management plan.

 Furthermore, `communication plays a vital role in project monitoring and control`, so project managers also must be good communicators with strong human resource skills. They _should_: 
 - regularly `update` stakeholders to ensure transparency
 - `manage expectations`
 - `facilitate` informed decision making.

 In addition, a crucial part of project monitoring and control is `managing risks`. This involves: 
 - `identifying` potential issues that can disrupt a project
 - `estimating` their impact
 - `developing` mitigating strategies
 - `monitoring` risks throughout the SDLC.


 ## Tracking 
 Tracking involves regularly collecting and analyzing project progress, budget, schedule and scope data. This should include tracking: 
 - milestones
 - deliverables
 - resources used
 - costs incurred. 

 Tools such as project management software can assist in `automating data collections` and `providing real-time insight.`

 ## Reviewing 
 Periodic reviews `compare` the projects `actual progress` with the `planned progressed`. In the context of a systems project, this could involve reviewing the results of each phase of the SDLC, such as _requirements analysis, design, implementation and testing._ 

 ## Regulating
Corrective actions are taken if deviations from the project plan or guiding quality standards are identified during the review process. For project planning issues, this could involve adjusting schedules, reallocating the resources, or modifying the project scope. For example, this might include revising design plans, reallocating developer time, or reassessing project priorities in a systems project.

 To help ensure that quality standards are met, many project managers institute structured walkthroughs. A **structured walkthrough** is a review of a project. Team members work by other team members. Generally, systems and analysts review the work of other system analysts, and programmers review the work of other programmers as form of peer review. Structured walkthroughs occur throughout the SDLC and are called **Design Reviews**, **Code Reviews**, or **Testing Reviews**, depending on the phase in which they appear.

 ## 3.9.2 Issue Resolution
A multitude of issues will inevitably rise across the SDLC, leading to projects derailing for various reasons. When problems occur, the project managers ability to resolve the situation becomes critical. When a project manager first recognizes that a project is in trouble, what options are available? Alternatives can include trimming the project requirements. Resources delaying the project deadline and improving management controls and procedures. Sometimes when a project experiences delays or costs overruns, the system can still be delivered on time and within budget if several less critical requirements are trimmed. The system can be delivered to satisfy the most necessary requirements, and additional features can be added later as a part of a maintenance or enhancement project.

If a project is in trouble because of a lack of resources or organizational support, management might be willing to give the project more commitment and higher priority. For example, management might agree to add more people to a project that is behind schedule. Adding staff, however, will reduce the project's completion time only if the additional people can be integrated effectively into the development team. If team members lack experience with certain aspects of the required technology, temporary help might be obtained from IT consultants or part time staff. Adding staff can mean training and orienting the new people, however. In some situations, adding more people to a project might actually increase the time necessary to complete the project because of a principle called Brooks Law. Frederick Brooks Junior, then an IBM engineer, observed that adding staffing to a late software project only makes it later. Brooks reached this conclusion when he saw that new workers on a project first had to be educated and instructed by existing employees, whose productivity was reduced accordingly.

 To succeed, an information system must satisfy business requirements, stay within budget, be completed on time and, most importantly, be managed effectively. As stated above and detailed below, when a project develops problems, the reasons typically involve business people, technology, budget or schedule issues. Therefore, in addition to planning and managing the project, project manager must be able to recognize these issues and deal with them effectively.

#### Case in Point 3.3 Just in Time software.
You are a system analyst at Just In Time Software, a company that specializes in short delivery cycles for its products. One of your projects is running behind schedule and the manager wants to bring in a few extra programmers to help with the work. You are familiar with the Brooks law. How can you explain to the project manager that adding more people to the project at this late stage may worsen things? You don't want to be seen as a negative team player, but you're convinced that the project's schedule will slip even more if you don't speak up. `(how would one word this withour offending someone in management?)`

 ## Business Issues
 The primary objective of every system is `to provide a solution to a business problem or opportunity`. If the system does not do this, then it is a `failure regardless of`:  
 - position reaction from users
 - acceptable budget performance or timely delivery. 
 
 When the information system `does not meet` business requirements, costs can include: 
 - unidentified or unclear requirements
 - inadequately defined scope
 - imprecise targets
 - shortcuts or sloppy work during systems analysis
 - poor design choices
 - insufficient testing or inadequate testing procedures
 - lack of change control procedures. 

 As explained elsewhere in the book. Projects without clear scope definitions are risky because they tend to expand gradually without specific authorization in a process called project creep. However, even when a project is clearly described, it must be managed constantly. Various business related challenges can arise from the intersection of technology and business operations and how changes in one affect the other. Understanding and addressing these business issues is crucial for the project's success. It requires a blend of technical expertise, business acumen, and strong communication and change management skills to navigate the complexities of business transformations. Three common business related problems that may arise are misalignment with business objectives, business process reengineering and ROI justification.

 ### Misalignment with business objectives.
 One of the primary challenges in systems projects. But the business objectives? The design system should support the company's strategic goals, whether increasing efficiency, improving customer service or driving innovation. If the system does not align with these goals or the business objectives changed during the project, it can lead to conflicts, wasted resources, and a system that doesn't deliver the expected value.
 New. New.


 Business Process re engineering.

 Implementing a new system often requires changing existing business processes, which can be a significant challenge. Employees may resist changes to their established routines, and there can be logistical challenges in reorganizing workflows. If these process changes aren't managed effectively, it can lead to disruption, decreased productivity, and potential failure of the new system.

 ROI justification.

 The cost of systems projects can be high and businesses often need to justify this investment by demonstrating a positive ROI. Calculating an ROI for such projects can be complex as benefits may be in direct or long term. If the system does not deliver the expected financial return or if costs are higher than anticipated, it can lead to dissatisfaction among stakeholders and jeopardize future projects.

 ## People Issues
 As described in Section 3.3, managing a systems project involves technical challenges and people issues. Three common people related challenges are a 
 - communication breakdown
 - resistance to change
 - skill gaps

  ### Communication breakdown.
  Effective communication is crucial for successfully completing a project. When there is a communication breakdown, misunderstandings can arise, causing confusion about project requirements, roles and responsibilities or project status. This can lead to errors, delays, and conflicts. For instance, if a systems analyst fails to communicate design specification clearly to the development team, the final system may not meet the intended user requirements.

### Resistance to change?
Introducing a new system often means changing to an organization's workflows, processes, or roles. People often resist change, especially if they it threatens their jobs or if they're comfortable with the existing system. Such resistance can slow project implementation and potentially cause the new system to fail once deployed.

### Skill gaps
Systems projects often involve using new technology or implementation innovative solution. The project can suffer if team members lack the necessary skills or knowledge. This could lead to errors, insufficiencies or delays. It could also lead to frustration among team members, lower morale and increased resistance to change.

## Technology Issues
System projects, by their nature, are heavily dependent on technology. While this resilience on technology offers many benefits, it can also introduce potential challenges. Managing these technologies issues requires staying abreast of the latest technologies and trends, robust planning and ongoing review throughout the project. A proactive approach to technology management can help anticipate and mitigate these challenges. Systems projects. The three common issues might arise technological compatibility, rapid technological change, and security and privacy concerns (Described in more detail later in the book)

### Technological compatibility
One of the frequent issues encountered in systems projects is technological compatibility. The new system may need to integrate with existing systems, platforms or software, and compatibility issues can arise during this process. For instance, there might be data format discrepancies, communication protocol mismatches, or different software requirements. These issues can delay the project and increased cost.

### Rapid technological change
Technological change is fast and what is considered state of the art technology today may become outdated tomorrow. A tool or technology chosen at the beginning of the project may become obsolete by the time the project is nearing completion. This can lead to inefficiencies, higher costs and even the need to reduce some parts of the project.

### Security and privacy
Data security and privacy are paramount in the digital age. When designing a new system, it's necessary to include robust security measures to protect sensitive data and ensure compliance with relevant news and regulations. However, designing for security is often complex and requires specialized knowledge. If not handled properly, security vulnerabilities can lead to data breaches, legal issues and a loss of trust among users.

## Budget issues
Systems projects involve significant financial planning and management. Despite the best efforts of project managers, budget related issues can still arise. Effective financial management, including accurate budget planning, regular financial review and proactive management of risks and changes can help mitigate these budget related challenges and keep the project on track.

 It's also essential to maintain clear and regular communication with all stakeholders about the project's financial status and any issues that arise to manage expectations and ensure informed decision making. Three common budget issues that may be encountered are cost overruns, unexpected expenses and inaccurate financial forecasting.

 ### Cost overruns
 One of the most common budget related problems is cost overruns. Where the projects actual cost exceeds the initial budget. This can occur due to unforeseen complexities, changes in project scope, also known as scope creep or underestimation of the expenses during the budgeting process. For example, if the price of hardware software licenses increase during the project or if additional personnel are needed, this can lead to increased costs that were not originally budgeted.

 ### Unexpected expenses
 Unexpected expenses can arise at any stage of the project, throwing the project budget off track. These could be related to technical challenges such as the need for additional software tools, hardware upgrades, or system reworks due to design flaws. Alternatively they could stem from non technical factors such as changing in regulation, market fluctuations affecting the price of resources or personal related costs.

 ### Inaccurate financial forecasting
 Accurate financial forecasting is crucial in budget planning for systems analysis and design projects. However, errors or oversights in the initial financial forecasting can lead to an unrealistic or unsustainable budget. This could involve underestimating cost, overestimating available funds or failing to account for potential risks and contingencies.

 ## Schedule issues.
 Proper scheduling is crucial in system projects to ensure that deliverables are completed on time and within budget. However, maintaining a project schedule can be challenging, and most projects run into at least some problems, including project delays, overlapping tasks, and underestimation of test duration. By moderating and controlling the work, the project manager tries to anticipate problems, avoid them, or minimize their impact, identify potential solutions and select the best solution.

 Effective project management, including detailed planning, regular progress tracking, and proactive problem solving, can help mitigate these scheduling issues. Using project management tools can also assist in visualizing the project schedule, identifying potential issues before they arise, and making adjustments as needed.

 The better the original plan, the easier it will be to control the project. If clear, verifiable milestones exist, it will be simple to determine if and when those targets are achieved. If enough milestones and frequent checkpoints exist, problems will be detected rapidly. A project planned was scheduled with PERT/CPM or in a WBS with Gantt. Charts can be tracked and controlled using the same techniques. As work continues, the project manager revises the plan to record actual times for completed tasks and adjust times for tasks that still need to be finished.

 ### Project delays
 Delays are one of the most common scheduling issues. They can occur due to various reasons such as unexpected technical challenges, changes in project scope, resource unavailability, or external factors like changes in mark conditions or regulatory requirements. Such delays can push back the project timeline, increasing cost and potentially causing stakeholder conflict.

 ### Overlapping tasks
 Problems with timetables in project milestones can indicate a failure to recognize test dependencies, confusion between effort and progress, poor monitoring and control methods, personality conflicts among team members, or turnover of project personnel. If test dependencies are not managed correctly, you might end up with overlapping tasks which can cause bottlenecks in the workflow. For example, suppose the design phase of a system is scheduled to begin before the analysis phase is complete. In that case it can lead to delays and inefficiencies as the design team may need more information to start their work.

 ### Understanding a test duration
 Estimating how long each task within the project will take is an essential part of scheduling. If test durations are underestimated, this can disrupt the project schedule. It's common to underestimate the time needs for tasks, especially in complex projects where certain tasks may be unfamiliar or unexpected challenge arise. There is an old saying that people overestimate what can be done in short term and underestimate what can be done in the long term. System projects are no different in this regard.

 # 3.9.3 Adopting an Agile Mindset
 Systems projects often involve complex dynamic requirements. In such cases, an agile mindset can be highly effective. Unlike traditional project management methodologies that try to define all requirements up front, the agile approach allows for flexibility and iterative developments where appropriate. An agile mindset can be adopted even when using a traditional project management approach. As described elsewhere in this book, in an agile project work is broken down into small manageable chunks or sprints, and each Sprint ends with a deliverable that can be reviewed and tested. This allows for regular feedback and adjustments, ensuring the final system is closely aligned with user needs. Moreover, agile methodologies emphasize regular reflection and continuous improvements in the product being the level developed and the team's working processes. An agile mindset also fosters an environment that encourages collaboration and teamwork, respects diverse perspectives, and constructively resolves conflict. This can lead to higher quality outcomes and a more engaged, effective project team.


