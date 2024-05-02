# **Spring Semester Team Software Project**

## Overview

In the spring semester, each team will implement a web system according to the user stories they collected in the autumn semester, where the requirements/stories for each team are expected to differ. The system will be delivered over _two iterations_, as per an agile software development strategy.

Each team will have a 15-minute meeting with their _supervisor_ every week, who will check progress and give informal feedback; you should also take the opportunity to ask for their opinion. Your supervisors will also view your demonstrations at the end of each iteration.

You will demonstrate progress on implementing and testing the system to your supervisor, who will provide you with feedback and assess whether the system meets the expectations as described in the autumn semester. After the first iteration, additional changes to the user stories will be requested based on what you have demonstrated and potentially due to Client additions/changes to requirements. The end of the second iteration marks the finalisation of development on the project and its delivery/handover.

We cover the technical aspects behind the development of the system during lectures and labs in Weeks 1–6. Please see Blackboard for lectures and labs. You can also use the same discussion board (Forum: Team Project - Client Questions) to communicate with the client, as you did in the autumn semester.

The overall timeline of the project is as follows:

| Iteration | Deadline | Deliverables | Semester Weighting |
| --- | --- | --- | --- |
| 1 | Friday 22 March, 15:00 (Week 7) | Report | 40% |
| 2 | Friday 10 May, 15:00 (Week 11) | Report, 15-min demo recording | 60% |

## Team Operating Agreement

Each team must have a **signed team operating agreement**, as explained in Semester 1. The template is available on the Blackboard (click this [link](https://vle.shef.ac.uk/bbcswebdav/pid-7099893-dt-content-rid-51488146_1/xid-51488146_1) or go to Semester 1 -> Course Content -> Lectures weeks 4-6 (Requirements) -> 6-1 Teamwork). It is a living document and should be updated as the need arises throughout the project.

If your team does not have a signed team operating agreement yet, create one as soon as possible. It will set out ground rules for working as a team and serve as an essential baseline in resolving disagreements and conflicts, if any.

## Weekly Schedule

You should schedule stories to implement according to your prioritisation of the client's requirements. However, your implementation plan may also be necessarily constrained by the order in which technical material is covered in lectures and labs. Therefore, check out the lecture schedule and plan the stories you will implement for each checkpoint and iteration accordingly. As stated above, do not try to deliver everything in the first iteration — teams will be marked down if they do this.

With all this in mind, here is a suggested week-by-week list of pointers for your team that you can use to check your plan of action:

| Week | Suggested Activities |
| --- | --- |
| 1 | You should be constructing the **basic views** for the system and what needs to be displayed on each "screen" of the application. |
| 2 | You should be thinking about which views require a form, and how data will be passed around the application – either through queries or by storing information in the session. |
| 3 | You should be thinking about which stories may require a **database** and how those may be tackled before the first iteration. |
| 4 | You should have completed some stories and have some tests in your application. |
| 5 | You should have a good set of **unit tests** by now and you should also be starting to identify integration tests as well as system tests (in the form of acceptance tests). |
| 6 | **Write different levels of tests (unit tests, integration tests, and**  **system** **tests)** to cover as much of your Iteration 1 stories as possible. Prepare for your team demonstration next week. |
| 7 | (Iteration 1 ends) Submit the **Iteration 1 report** as a PDF. Ensure your repository is up to date. Prepare and rehearse your live **demonstration** of your system for your supervisor meeting this week. |
| 8 | Decide, as a team, how you're going to **make changes** as a result of feedback and any new requests. |
| 9-10 | Time to meet up and make sure that everything integrates well and is consistent. Check your code style and conduct **refactoring** if needed. |
| 11 | (Iteration 2 ends) The Iteration 2 deadline is this week. Time to finish up on implementation and testing. Prepare and rehearse your final **live demonstration**. Submit your **final team report and 15-min demo recording**. |
| 12 | Don't forget to complete the **peer review** by Friday. |

# Report

Iteration 1/2 reports should include the following information:

- Team ID, members, and the summary of each member's major contributions.
  - A map between each member's name and their GitLab user name, especially if you accidentally made commits under your private emails.
- The exact command(s) needed to install and start your system.
- The exact command(s) needed to run your tests.
- The predefined usernames (e.g., admin1, reader1) for inspecting your system.
  - For each account, the password must be the same as the username.
- A list of all your user stories with their status (e.g., to-do, in-progress, or done) and changes (e.g., modified, removed, or newly added).
  - Please cluster stories about the same type of user.
  - Use colours and highlights to distinguish different statuses and changes, as shown in Figure 1 below.
- What you have done in terms of testing (e.g., unit tests, integration tests, and system tests).
- (Iteration 2 only) What you have done in terms of refactoring.
  - You should present *concrete examples* along with your refactoring *summary* to demonstrate the quality of your refactoring.
  - When you include code fragments, you must use source code colouring, line numbers and a proper caption, as shown in Listing 1 below.
- Your burndown chart, showing progress over all of your stories over each iteration.
- Overall, use figures and tables with clear captions, wherever appropriate.
- (Optional) Please append your team operating agreement signed by all team members to the report as an appendix. This is not subject to assessment, but we will use this as a baseline in resolving disagreements and conflicts, if any.
- (Optional) If you have some internal meeting notes/minutes recording attendees, issues, and task distributions during your internal meetings (not the team supervisor meetings), please append those meeting notes/minutes as an appendix to the report. If needed, you can sanitise sensitive information and keep only the important parts mentioned above.

<img width="600" alt="figure-1" src="https://github.com/UoS-COM1001/com1001-2024/assets/12538465/d9180dc0-9e6a-424a-b679-a67e158425ee">
<img width="600" alt="listing-1" src="https://github.com/UoS-COM1001/com1001-2024/assets/12538465/55180e37-1a7b-41ad-af7c-d7c201525707">


## Code Commits to the Team Repository

At the end of Iteration 1, we may inspect your code, but mostly for clarification.

At the end of Iteration 2, we will look at **the last commit** to the team's repository **before the deadline** for the assessment.

- Ensure all the **necessary files** are committed to your team repository **by the deadline**. Otherwise, you will not receive the mark you deserve.
- We will _not_ check out other repositories (e.g., your personal repository from the last semester, or another Git repository).
- **All members** should be making **regular commits**. We will check that you have been making regular commits – not just one or two commits or a sudden rush of commits just before the deadline.
- We will use **Codio** to run and test your code. Therefore, it is strongly recommended that you develop on Codio; otherwise, you must at least deploy often to Codio as it is the required deployment platform.
- We will use **README** to run and test your code. Ensure that your README is up to date and contains the necessary information to run and test your system.
- Ensure that your `Gemfile` is up to date. If we cannot run your application on Codio due to missing gem information, this will severely negatively affect your mark.
- (Pro-tip) Attempt a **clean install** before your final commit to check whether your system is successfully deployed and running on Codio.

## Live Demonstrations

The demonstration meetings will be held with your supervisors during the standard Team Supervisor meeting times Weeks 7 and 11. In these meetings, you will demonstrate the current state of your system for feedback (as if to the client). For this, you should prepare a **10-minute live demonstration** of your system. If possible, let your supervisor try out your system and get feedback. You will have a few days to update your system for the recording you will upload to your repository by Friday.

Here are some remarks for you:

- Be on time.
- Do a rehearsal before the live demo.
- It's for the client – make it easy to follow.

## Team Contribution

Similar to the last semester, you will be using BuddyCheck to rate yourself and your team members on the following criteria:

1. Attendance and punctuality (to supervisor/your own team meetings, etc.).

2. Ability to work effectively with other team members.

3. Quality of contributions.

4. Timeliness of contributions.

Your final individual mark will be formed from a scaling factor that is applied to your overall team mark. The scaling factor is determined by your own self and peer assessment, and those returned by your team members. 

Note: The Department's Policy on Team-Based Assessments requires evidence to support an individual mark varying by more than +/-15% from the team mark; the evidence considered will include Supervisor meeting attendance/notes as well as Slack/GitHub interactions.

## Marking Criteria

The following table details the criteria against which your team's work will be marked. You will receive a mark sheet containing a table with marks and feedback against the aspects detailed below. Each aspect is marked out of 100. The overall mark is the average of each of the marks for each aspect.

Note: (2) indicates for iteration 2 only, and (1+2) indicates for both iterations.

| **Aspect (iterations)** | **Indicative Criteria** |
| --- | --- |
| Implementation Progress (1+2) | **Iteration 1**: The amount of work completed to date, the extent to which you are on track to delivering a good quality product and the appropriateness of stories implemented in this iteration. <br/> **Iteration 2**: The completeness and quality of your final system. The extent to which it implements the Client's requirements, how usable it is, how polished it is, and the extent to which it crashes and/or throws errors. |
| Code Quality (1+2) | The quality of your code, including good coding principles, such as useful variable names, code comments, etc. The basic organisation of your code into units, and its overall structure. |
| Testing (1+2) | The quality of your automated tests, including unit tests, integration tests, and system tests. The extent to which you have justified the level of coverage that you have obtained. |
| Demonstration (1+2) | The quality of your team demonstration. The extent to which it demonstrates major user stories effectively within the limited time. |
| Report (1+2) | The quality of your team report, the extent to which it details all the requested information, including changes to stories, basic information about using your system etc. |
| Refactoring (2) | The quality of your refactoring. The extent to which your team has clear evidence of refactoring efforts written in the report. |
| Deployment (2) | The extent to which it was easy and straightforward to deploy and get your system running—on the basis of your instructions and the implementation of your deployment process—from Git checkout to the commands needed to start the application. |

## Unfair Means

It is essential to bear in mind the departmental rules on unfair means. Activities such as **plagiarism** or **collusion** will be treated as serious academic offences. This could lead to the award of a grade of zero for your submission.

We will be closely scrutinising submissions to detect such practices because it is important that this team project is a genuine reflection of your own understanding of the module.

To avoid any potential accidental wrongdoings, it is especially important that you do not discuss your solutions with other groups. If you have non-technical questions, please use the discussion board (Forum: Team Project - Non-coding Issues). If you have technical questions, please consult with your demonstrators.

We acknowledge that **Generative AI**, such as Google Bard and OpenAI ChatGPT, can be useful in learning. For example, it is okay to use Gen-AI to try various programming exercises. However, **the use of Gen-AI is prohibited in any of your submissions** subject to the assessment (i.e., the reports and the code commits to the team repository). For example, you must _not_ use the code generated by Gen-AI in the code pushed to your team repository. It is crucial that you learn by doing the project by yourself, and gaining an unfair advantage through the use of Gen-AI in the assessment will be treated as unfair means.
