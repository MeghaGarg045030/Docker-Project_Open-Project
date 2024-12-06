# Setting up Open Project using Docker Desktop

#### INTRODUCTION

The purpose of this project is to deploy **OpenProject**, an open-source project management software, using Docker Desktop. This exercise demonstrates how containerization simplifies software deployment and provides a scalable, efficient way to run applications. Through this project, we explore concepts such as Docker image containers, port forwarding, and software accessibility via localhost.

![image](https://github.com/user-attachments/assets/843e6d98-9594-4d35-adba-df7b056e8d87)

<br>
<br>

#### ABOUT OPEN PROJECT

OpenProject is an open-source project management software designed to provide organizations with tools for effective collaboration, planning, and monitoring of projects. It offers features such as task management, Gantt charts, Agile and Scrum boards, time tracking, and more. OpenProject’s open-source nature allows developers and organizations to customize and extend the software based on specific requirements.

![image](https://github.com/user-attachments/assets/eb1825b9-36a2-4fdb-ab3d-27315b19fbff)

<br>
<br>





### **COMMAND TO RUN OPEN PROJECT IN DOCKER**
 
 **docker run -it -p 8080:80 -e OPENPROJECT_SECRET_KEY_BASE=secret -e OPENPROJECT_HOST__NAME=localhost:8080 -e OPENPROJECT_HTTPS=false -e OPENPROJECT_DEFAULT__LANGUAGE=en openproject/openproject:15**

- This command runs the OpenProject application in a Docker container.
- The application is accessible locally at **http://localhost:8080** with HTTPS disabled and English set as the default language.
- The environment variables allow flexible configuration during runtime, and the 15 tag ensures a specific version of OpenProject is deployed.
  

<br>


### OPEN PROJECT DEMO VIDEO



https://github.com/user-attachments/assets/902de4da-d431-4e02-9a22-f56113245197



<a href="https://www.openproject.org/docs/installation-and-operations/installation/docker/">Link for the Source Code</a>



