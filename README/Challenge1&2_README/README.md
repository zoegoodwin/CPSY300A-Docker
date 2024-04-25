# docker-challenge-template

# Project Title: Docker Challenges

## Introduction

You are currently viewing the README.md file for my Docker challenge repository.
This was done as a bonus assignment for my Operating Systems (CPSY-300) course.
By completing these challenges, I learned the basics of Docker, container management, and how to deploy both static and dynamic web applications.

## About This Repository

This repository contains all the work I've done for the Docker Challenges.
Here, you will find Dockerfiles, docker-compose files, screenshots, and my journal documenting each step of my journey.
To briefly explain, challenge 1 involved setting up a simple static website using Docker whereas challenge 2 was about running a dynamic web app with Docker's help. 


### `student.cfg`

Contains my student information, including:

- Name: Zainul Malik
- Student ID: 000909370


## Project Structure

- **README.md**: The file you are currently reading! It provides an overview of the project, including an introduction, repository 
  contents, and a detailed report of my learning experience and findings.
- **student.cfg**: Holds my personal student information.
- **challenge1/**: Contains the first Docker challenge, which focused on deploying a static web page 
  using Docker.
- **challenge2/**: Includes the second Docker challenge, in which I had to create a dynamic 
  application with Docker Compose. API server and a reverse proxy setup files were also used which were found in the challenge2.zip file.


## Learning Experience and Findings

While completing this assignment, I gained a lot of hands-on experience with Docker and was able to learn the basics.
I learned the basics of simpler topics such as containerization to more advanced topics like managing many containers using 
Docker Compose and also using reverse proxy servers (challenge 2). More detail can be found below:

- **Docker Basics**: I learned how to create/write Dockerfiles, build images, and run containers. 
  Along with this, I learned the fundamental concepts of containerization and its benefits over more traditional 
  virtualization.
- **Static Web Page Deployment**: I was able to successfully deploy a static web page using Docker and 
  NGINX which showed my name and student id. This allowed me to understand the process of serving static assets through containers.
- **Dynamic Application Deployment**: Learned how to use Docker Compose to set up a web app (NodeJS) and how to use NGINX to direct traffic to it.
  how different services can be linked and managed.
- **Debugging and Troubleshooting**: Learned to fix issues and challenges related to issues such as container 
  networking and configuration. For example, when my web app wasn't able to be reached through NGINX I figured out it was due to misconfiguration in the proxy settings.
  Overall, this helped me to get even more comfortable with Docker as I was able to not only write/create Dockerfiles but also how to solve issues surrounding them, which 
  is a very useful skill to have.

## Conclusion

This assignment was a great opportunity for me to learn a very useful and modern software called Docker. 
The challenges helped me to gain a basic understanding of this software and how it can be utilized to create, deploy, and manage apps in a more efficient way. 
Challenge 1 taught me how to successfully deploy a static web page, and Challenge 2 introduced me to the complexities of managing dynamic applications, showing me how to use Docker Compose to run multiple containers and setting up NGINX as a reverse proxy for
smooth interaction between the user and the application. Overall, this hands-on experience has given me valuable knowledge about Docker and containerization which will be very useful for me in my future education and career.
