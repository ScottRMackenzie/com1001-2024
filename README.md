# COM1001 – Introduction to Software Engineering <br /> Spring Semester 2024

# Advice for the Module - From Me (Student who sat the module)
These are notes and advice that I would have like to have had before sitting the module. <br><br>
The module is a year long and is split into two main group activities split between the semesters. You will be in the same team for both semesters.

## 1. First Semester
In the first semester, you will have lectures and assessments as well  as a coursework team project.
For the team project, you will be put into a team that you will be with for the entire module. You then will be given a "real" client who will require you to build them some sort of application or a website with both front end and backend development.

For the project in this repo, we was give the task to make a book publishing platform using Sinatra (Which is basically simplified ruby on rails and is quite easy to learn)

### The Task
The main task of the first semester is to create a requirements document which will create story cards that each contain user stories and acceptance criteria. I would recommend that you also include statistics such as a ranking of each story on how critical they are to meet the clients needs and the scale of the complexity of an implementation. (Remember that these figures are just estimates so don't have to be exactly realistic but needs to be in line with your other stories)

Each story card should be split into the groups for each of the of stakeholders provided. (E.g. for a book publishing platform, the stakeholders where readers, writers and staff members.) The stakeholders should be provided in your clients requirement slides.

You should have a minimum of 50 story cards all together but remember quite a lot of these can be simple like logging in, logging out, creating an account, ect.

Your mark may be influenced by your layout so use some sort of grid system for the best clarity and possible marks.

Finally remember that you will need to implement almost all of what you created in your story cards (3 MAX that you don't implement) so keep them rather simple and easyish to implement.

## 2. Second Semester

- TBA

___
# The Original README
Welcome! This repository contains information, code examples, practical sheets, and slides to support the Spring Semester of the COM1001 module "Introduction to Software Engineering" at the University of Sheffield.

Jump to:
* [1. Primary Teaching Staff](#1-primary-teaching-staff)
* [2. Getting Started](#2-getting-started)
* [3. Schedule and Resources](#3-schedule-and-resources)

## 1. Primary Teaching Staff

  |<img src="./misc/phil.jpg" width="150"/> | <img src="./misc/donghwan.jpg" width="150"/>|
  |:----------------------------------------:|:--------------------------------------------:|
  | [Phil McMinn](https://mcminn.info) <br /> Lectures & Labs | [Donghwan Shin](https://www.dshin.info) <br /> Team Project |

## 2. Getting Started

Before you start with anything, you need to get Codio setup so that you can  run the examples in this repository, and eventually, develop your team project. To do this, follow the instructions on the [Getting Started](./getting-started/README.md) page.

If you **encounter technical problems or issues**, you'll need to consult the [Technical FAQ](technical-FAQ.md). Importantly, this page tells you what to do if your particular question or issue is not specifically addressed by the FAQ itself. 

The [Group Project Brief](Spring-Project-Brief.md) will give necessary details about your group project and assessments. If you have any questions regarding that, please consult the [Project FAQ](https://github.com/UoS-COM1001/com1001-2024/blob/main/project-FAQ.md) and use the Discussion Board/Forum. 

## 3. Schedule and Resources

Materials for the module can all be found in this repository, which consists of directories corresponding to content for each week. Files will be added as we proceed through the module, so ensure that you regularly do a `git pull`.

| Week | Lecture | Practical Session | Resources | Supervisor Meeting | Deadline |
|-:|-|-|-|-|-|
|Pre   | | | [getting-started/](./getting-started/) |
|1     | <ul><li>HTTP – a review</li><li>An Introduction to Sinatra</li><li>Controllers</li><li>Views</li><li>Queries</li></ul>| [Getting everything setup](week1/practical.md) | [week1/](./week1/) | *No meeting* | |
|2     | <ul><li>Forms</li><li>Sanitisation & Validation</li><li>GET and POST</li><li>Sessions</li></ul> | [Starting to Develop Your Team Web Application](week2/practical.md) | [week2/](./week2/)| Catch-up | |
|3     | <ul><li>Databases</li><li>Object Relational Mapping</li><li>Data Confidentiality</ul> | [Databases & Models](week3/practical.md) | [week3/](./week3/) | Catch-up | |
|4     | <ul><li>Guest lecture: **[A Career in Ruby](./week4/guest-lecture.md)**, Matthew Valentine-House (Shopify)</li></ul> | [Queries and Forms](week4/practical.md) | [week4/](./week4/) | Catch-up | |
|5     | <ul><li>Why Write Automated Tests?</li><li>Using RSpec to Automate Unit and Integration Tests</li><li>Using Capybara with RSpec to Automate Acceptance Tests</li></ul> | [Testing](week5/practical.md) | [week5/](./week5/)| Catch-up | |
|6     | <ul><li>Using Code Coverage as a Tool for Testing</li><li>Debugging</li><li>Refactoring</li></ul> | [Coding Standards and Refactoring](week6/practical.md) | [week6/](./week6/)| Catch-up | |
|7     | *No lecture* | *No session* | | Demo | Iteration 1 <br /> Fri 22 Mar, 15:00 |
|Easter|
|8     | *No lecture* | Team Project Help | | Catch-up | |
|9     | *No lecture* | Team Project Help | | Catch-up | |
|10    | *No lecture* | Team Project Help | | Catch-up | |
|11    | *No lecture* | *No session* | | Demo | Iteration 2 <br /> Fri 10 May, 15:00 |

### Lectures

Lectures will be held on **Tuesday mornings 9am-12noon (week 1) / 10am-12 noon (weeks 2-6) in St George's Church**. There will be a break during the 2 hour lecture, and also a (non-assessed) team quiz. There will be a prize in week 6 for the team that performs best overall in the quizzes. 

### Practical Sessions (Labs)

Practical sessions will be held on **Fridays 1-2pm in the [Diamond](https://www.sheffield.ac.uk/engineering/diamond-engineering/floor-plans) from week 1 until week 10** (but excluding week 7). The practical sessions consist of team exercises, coding challenges, and will offer practical technical help regarding the team project. You will need to bring your own laptop to this session, or use the laptop loan facility.

Where you go and where you sit depends on which team you're in:

* **Teams 1-26** need to go to **Computer Room 3** on the second floor, and follow the [seating plan for CR3](misc/CR3-seating-plan.pdf).
* **Teams 27-53** need to go to **Computer Room 5** (formerly known as the Mindsphere lounge) on the ground floor, and follow the [seating plan for CR5](misc/CR5-seating-plan.pdf).

### Supervisor Meetings

Each team will be allocated a supervisor (a member of the department's teaching staff). Each team will meet with their supervisor once a week, **starting in week 2 and finishing in week 11**. These meetings will happen on **Tuesday afternoons between 1-3pm in Computer Room 5** (formerly known as the Mindsphere lounge) on the ground floor of the Diamond. You only need to attend a 15-minute meeting in this two-hour block. The exact time of your team meetings and the seating plan is available [here](misc/CR5-seating-plan-supervisor-meeting.pdf). 

There are two types of meetings – "Catch-up" and "Demo". During **"Catch-up" meetings**, supervisors will discuss with you how your project is going and check that all your team members are engaged with it. **Demo meetings** are where you will demonstrate your work to your supervisor. These meetings will happen in the week prior to handing in your work for Iterations 1 and 2. For the demo, your team will need its own device to showcase your work – or, you can use the laptop loan facility.

Note: your team supervisor will focus on monitoring your progress and teamwork, *not* providing technical advice on your project. Technical advice will be available (via the demonstrators) in the scheduled practical sessions listed above. 

