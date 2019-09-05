# major-1
1	Project Title
Automating DevOps Project
2	Abstract
For developing any kind of application, it involves numerous and different phases. These phases include development, operation, deployment, testing and monitoring of application. There are DevOps tools which can be used to automate all these processes respectively. Our goal is to automate the whole process of application development, not just a single phase. As demands for various products are increasing, we need faster development of the products. The application developed needs to be error free. So to achieve this we are automating the whole cycle of product development i.e. each and every major phase of it.

In our system, one doesn’t have to worry about all these phases of the application but to write the code only. Our system will take care of the whole development process of the application. User has to give the code and all the processes will be done by our system automatically. It takes the code; put it into appropriate development cycle and test it with the expected outcome. All this is done automatically. This will make the development of the application fast. The product will be less error prone as human intervention would be negligible.
Keywords: DevOps, Automation, Jenkins, Docker, JUnit, Selenium.
3	Introduction
Automation is an important aspect for faster development of anything. This reduces the manual effort and makes the development faster. It also reduces the error in the application. A person or an organization can put their time and effort more on writing the code. They would get more time for adding features to their product. They don’t have to take care of the deployment and testing of their applications.

Automation improves the performance. It does so by improving the time to come in market and improving quality. It also reduces the error as human tends to make mistake. 

In this project we are using different technologies like VCS, Jenkins, JUnit, Selenium. VCS is used to put the code. The code is extracted from the VCS. VCS helps in managing the source codes and keeps every version of the code. It helps in better collaboration in a team.

Jenkins is used for continuous integration and continuous deployment. It is an extensible automation server. It can be used as a simple CI server or turned into the continuous delivery for any project. It can easily distribute work across multiple machines, helps in drive builds, tests and deployments across multiple platforms faster. Because of this Jenkins is preferred over other tools.


 
Figure: DevOps + Continuous Delivery Cycle

4	Literature Review

Automation of Devops is emerging idea which is aimed to decrease human interaction in software development process and decrease time and cost of development of software. Devops is burning technology in the recent days have lots of studies and research in processs and Automation of Devops project is one of them.

In paper [1] by Waller, Jan, Ehmke, Nils Christian and Hasselbring, Wilhelm (2015) Including Performance Benchmarks into Continuous Integration to Enable DevOps ACM SIGSOFT Software Engineering Notes, 40 (2). pp. 1-4. DOI, and quote: The DevOps movement intends to improve communication, collaboration, and integration between software developers (Dev) and IT operations professionals (Ops). Automation of software quality assurance is key to DevOps success. We present how automated performance benchmarks may be included into continuous integration. As an example, we report on regression benchmarks for application monitoring frameworks and illustrate the inclusion of automated benchmarks into continuous integration setups.

In paper [2] by Nina Marweide, Matthaisa Rohr, Andre Var Hoorn (2009) Automatic Failure Diagnosis Support in Distributed Large-Scale Software Systems Based on Timing Behavior Anomaly Correlation, and quote: Manual failure diagnosis in large-scale software systems is time-consuming and error-prone. Automatic failure diagnosis support mechanisms can potentially narrow down, or even localize faults within a very short time which both helps to preserve system availability.


5	Problem Statement

To develop even a simple application, one invests lot of time in it. It is so because they have to take care of the whole process of the application development cycle. It involves development, deployment, operation, testing and monitoring. To reduce time in production, presently there are some tools which provide automation in each phase. But still developer needs to configure each one of those by themselves. So it is better to automate the whole process starting from the code till its deployment and monitoring.

Problem has Input as:
Developer’s code.

And Output as:
Generate report



6	Objectives
Automation of all the processes in the development of application/software starting from the user’s (i.e. developer) code.  System will show the report generated from the user’s code. The system will help the developers in increasing their rate of application development. It also makes application less error prone. Automation helps developer to devote more time on enhancement of the features of the application. Automation is done to  reduce the human effort and makes the developer’s more profitable.
Sub-Objective:
•	Automation of fetching project source code from version control system (Github).
•	Automation od CI/CD processes on Jenkins using Selenium web driver
•	Automation of project deployment on tools like Apache server
•	Automation Testing of project build and deploymen

7	Methodology
Selection of a particular type of life-cycle model depends largely on our project scope and stakes.
In our project, we are following agile model and according to this model, project development is very much flexible and requirements can be added at any stage of project development. 
In this process we are using following tools and technologies: -
•	Selenium
•	Jenkins
•	Github
•	Junit
Step-1: Fetch project from Github. Identify the type of project i.e. whether it is web application or angular project or any other type of devops project.
Step-2: Based on project type and requirements, automate the project’s build and deployment using selenium.
Step-3: Use Junit to verify whether the build is successful or not. Further we will confirm whether the project is giving desired output by providing various test cases through unit testing.

8	System Requirements (Software/Hardware)
•	Hardware Interface:
–	64 bits processor architecture supported by windows.
–	Minimum RAM requirement for proper functioning is 4 GB.
–	Required input as well as output devices.
•	Software Interface:
–	This system is developing in Python programming language.
–	Python interpreter.


