# Star_Cement_Project_Management

# MS-Project_Peerless

**GitHub Link:** https://github.com/toarnabtrainer/Star_Cement_Project_Management<br>
**or** https://tinyurl.com/yc4tcj6u

![image](https://github.com/toarnabtrainer/Star_Cement_Project_Management/assets/111301975/0beb0d5c-9705-495c-a16a-3d467b1c65eb)

<hr>

**PERT - Program Evaluation Review Technique**<br>
**Three-point analysis:**<br>
* **Most Likely Estimate (M)** = Estimate of the most likely value of the duration <br>
* **Optimistic Estimate (O)** = Estimate of the duration under the most favourable conditions <br>
* **Pessimistic Estimate (P)** = Estimate of the duration under the most unfavourable conditions <br>

**PERT = (P + O + 4M) / 6**<br>
**Standard Deviation = (P - O) / 6**<br>
**Variance = Standard Deviation ^ 2**<br>

**Note on BCWS, BCWP and EVM Variables available in this link:**<br>
https://acqnotes.com/acqnote/tasks/budgeted-cost-of-work-scheduled#:~:text=BCWS%20%3D%20Budgeted%20Cost%20of%20Work,Actual%20Cost%20of%20Work%20Performed <br>
and<br>
https://www.pinnaclemanagement.com/blog/earned-value-management-an-introduction#:~:text=Earned%20Value%20Management%20(EVM)%20is,extent%2C%20schedule)%20at%20completion.

* **Project 2021 Beginner Tutorial (2 Hours 27 Minutes):** https://www.youtube.com/watch?v=l3ypMRwW9tc
* **Project 2021 Advanced Tutorial (3 Hours 11 inutes):** https://www.youtube.com/watch?v=NnVLgvvkBo8
* **Project 2019 Advanced Tutorial (2 Hours 10 inutes):** https://www.youtube.com/watch?v=xc38Om2HtBA
* **MS-Project 2016 Step by Step Tutorial PDF:** https://tinyurl.com/bdfauhz8
* **MS-Project TutorialsPoint Tutorial PDF:** https://tinyurl.com/5zm6np2t

**PERT Calculations in MS-Project:**
Based on the problem given in the file "Introduction to Project Management.pptx"
* My_O (Number1) Put values in the column manually.<br>
* My_M (Number2) Put values in the column manually.<br>
* My_P (Number3) Put values in the column manually.<br>
* My_PERT (Number4) => ([Number1]+4*[Number2]+[Number3])/6<br>
* My_PERT_Round (Number5) => IIf([Number4]-<br>
Int([Number4])>=0.5,Int([Number4])+1,Int([Number4]))<br>
* My_PERT_Ceil (Number6) => IIf([Number4]-Int([Number4])>0,Int([Number4])+1,Int([Number4]))<br>
* My_PERT_Floor (Number7) => Int([Number4])<br>
* My_PERT_Variance (Number8) => (([Number3]-[Number1])/6)^2<br>
* My_PERT_StdDev (Number9) => Sqr([Number8])<br>

**MS-Office/O365 Reference Tutorial Links -**<br>
* **MS-Office 2007:** https://edu.gcfglobal.org/en/topics/office2007/
* **MS-Office 2010:** https://edu.gcfglobal.org/en/topics/office2010/
* **MS-Office 2013:** https://edu.gcfglobal.org/en/topics/office2013/
* **MS-Office 2016:** https://edu.gcfglobal.org/en/topics/office2016/
* **MS-Excel Formulas:** https://edu.gcfglobal.org/en/excelformulas/
* **50 Tips to Master Excel ebook:** https://drive.google.com/file/d/0ByEvd0vhZtF3Zm9tY09YNWpuUnM/view
* **How to remove password from an Excel Worksheet:** https://www.youtube.com/watch?v=fsVb6id97_E&list=PLmkaw6oRnRv9uEamCt-PXS-bP-rmoxcLc&index=3
* **MS-Excel Cheat Sheet:**	https://drive.google.com/file/d/1dGDoOiIhFFD71FxUxMO-ZYYE2UYLNGhR/view?usp=sharing

<hr>

# Agile_Project_Management

## Agile Team Roles
### Development Team/Delivery Team
<pre>
  This group includes everyone needed to build and test a complete increment of the product, such as coders,
  writers, designers, analysts, and testers. Agile delivery teams rely on generalizing specialists—people who
  can perform multiple jobs and switch from role to role as the demand arises. These team members:
  
  » Build the product increments, using agile practices and processes.
  » Regularly update information radiators to share their progress with stakeholders.
  » Self-organize and self-direct their working process within an iteration.
  » Share their progress with each other in daily stand-up meetings.
  » Write acceptance tests for the product increments.
  » Test and revise the product increments until they pass the acceptance tests.
  » Demonstrate the completed product increment to the customer in the iteration review meeting.
  » Hold iteration retrospectives to reflect on their process and continually improve it.
  » Perform release and iteration planning, including estimating the stories and tasks.
</pre>
### Product Owner/Customer/Proxy Customer/Value Management Team/Business Representative
<pre>
  » Maximizes the value of the product by choosing and prioritizing the product features.
  » Manages the product backlog, making sure that it is accurate, up to date, and prioritized by business value.
  » Makes sure the team has a shared understanding of the back log items and the value they are supposed
    to deliver.
  » Provides the acceptance criteria that the delivery team will use to prepare acceptance tests.
  » Determines whether each completed product increment is working as intended, and either accepts it or
    requests changes (in the iteration review meeting).
  » May change the product features and their priority at any time.
  » Facilitates the engagement of external project stakeholders and manages their expectations.
  » Provides the due dates for the project and/or its releases.
  » Attends planning meetings, reviews, and retrospectives. (If this role is performed by a group of people,
    typically only one or two of them will attend these meetings.)
</pre>
### Scrum Master/Coach/Team Leader
<pre>
  » Acts as a servant leader to the delivery team, helping them improve and removing barriers to their progress.
  » Helps the delivery team self-govern and self-organize, instead of governing and organizing them.
  » Serves as a facilitator and conduit for communication within the delivery team and with other stakeholders.
  » Makes sure the delivery team’s plan is visible and its progress is radiated to stakeholders.
  » Acts as a coach and mentor to the delivery team.
  » Guides the team's agile process and makes sure their agile practices are being used properly.
  » Helps the product owner manage the product backlog.
  » Helps the product owner communicate the project vision, goals, and backlog items to the delivery team.
  » Facilitates meetings (planning, reviews, and retrospectives).
  » Follows up on issues raised in stand-up meetings to remove impediments so that the team can stay on track.
</pre>
### Project Sponsor
<pre>
  » Serves as the project’s main advocate within the organization.
  » Provides direction to the product owner role (the person or team representing the business) about the
    organization’s overall goals for the project.
  » Focuses on the big picture of whether the project will deliver the expected value on time and on budget.
  » Is invited to the iteration review meetings to see the product increments as they are completed, but
    might not attend.
</pre>
<hr>
