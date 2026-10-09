# Laboratory 07 – Cloud Operations Engineer

## Mission Overview
Congratulations! Your ability to deploy multi-tier architectures has proven your technical capabilities.
You have now been promoted to the Cloud Operations Team (often referred to in the industry as Site Reliability
Engineering, or SRE) at CloudNova Technologies.
Deploying a cloud application is only the first step; keeping it running smoothly is the real challenge.
When a server crashes or a web page takes ten seconds to load, you cannot simply guess what is wrong. You
must rely on Observability and Monitoring to see inside your infrastructure.
Using the KillerCoda Playground, you will step into the role of a Cloud Operations Engineer. You will
establish a performance baseline for your Linux server, deploy a containerized application, generate artificial web
traffic, and hunt down performance metrics and system logs to prove the application is healthy.
Remember: A developer hopes the application works; a Site Reliability Engineer uses metrics and logs to
prove it.


## Objectives

At the end of this laboratory activity, you should be able to:
- Utilize native Linux command-line tools to monitor host CPU, Memory, and Disk capacity.
- Deploy a web container and track its real-time performance using Docker metrics.
- Generate web traffic and extract application access logs for analysis.
- Translate raw performance data into a readable technical report using Markdown.
- Continue expanding a professional GitHub Cloud Computing Portfolio. 


## Monitoring Commands Executed

| Command | Purpose |
|---|---|
| `free -h` | Check RAM usage |
| `df -h /` | Check root filesystem storage |
| `top` | Monitor CPU activity and running processes |
| `docker run -d --name clientwebsite -p 8080:80 nginx` | Deploy the Nginx container |
| `curl -i http://localhost:8080/` | Test the web server |
| `curl -i http://localhost:8080/hidden-admin-page` | Generate an HTTP 404 response |
| `docker logs clientwebsite` | Retrieve application logs |
| `docker stats` | Monitor real-time container metrics |

## Skills Learned

Through this laboratory activity, I practiced using Linux commands to inspect system resources, deploying a containerized web server, testing HTTP responses, analyzing application logs, and observing Docker performance metrics. I also learned the importance of documenting actual monitoring results and keeping screenshots as evidence.
