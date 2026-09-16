# Laboratory 04 - The Cloud-Native Engineer

## Mission Overview

Congratulations! After successfully guiding our clients through multi-cloud evaluations, you have been
promoted to the Cloud-Native Engineering Team at CloudNova Technologies.
Modern cloud computing is no longer just about renting Virtual Machines (VMs) from AWS or Azure. Today's
enterprise applications are built using lightweight, portable, and lightning-fast technologies called Containers.
Your new mission is to understand the shift from traditional virtualization to containerization.
Using the KillerCoda Playground, you will step into the shoes of a Cloud-Native Engineer. You will research the
differences between VMs and containers, execute your very first Docker commands, and deploy a live,
containerized web server in seconds.
Remember: A traditional system administrator manages servers, but a cloud-native engineer manages
the services running on them.

## Objectives
At the end of this laboratory activity, you should be able to: 

- Differentiate between traditional Virtual Machines (VMs) and Containers
- Access a Docker-enabled cloud environment using KillerCoda. 
- Execute fundamental Docker CLI (Command Line Interface) commands.
- Pull, run, manage, and terminate a containerized application (Nginx).
- Create professional technical documentation of container operations using Markdown.
- Continue developing a well-organized GitHub Cloud Computing Portfolio.


## Docker Commands Executed
```bash
docker --version
docker info
docker pull nginx
docker run -d --name nginx-server -p 8080.80 nginx
curl http://localhost:8080
docker ps
docker stop nginx-server
docker ps -a
docker rm nginx-server
```
## Skills Learned
Through this activity, I learned how to use basic Docker commands and how containers can be used to deploy applications. 
I learned how to pull an image, run a container, map ports, test a web server, and manage the container lifecycle.
## Challenges Encountered
One challenge I encountered was understanding the purpose of Docker commands and the difference between a Docker image and a container.
