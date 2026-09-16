# Mission Reflection

This laboratory activity helped me understand the difference between virtual machines and Docker containers. A Docker container can start faster than a virtual machine because it does not need to start a complete operating system. Instead, it uses the host computer's operating system and runs the application it needs. Installing an operating system on a virtual machine takes more steps, such as setting up storage and memory and waiting for the operating system to start. Docker can run an application quickly using a prepared image.

Port mapping is needed because the web server inside the container uses port 80, while users access it through the host computer. The `-p 8080:80` command connects port 8080 on the host to port 80 inside the container. This allowed me to open the Nginx web server using `curl http://localhost:8080`. Without port mapping, accessing the web server from the host would be more difficult.

When the `docker rm` command is used, the selected container is deleted. The files and changes saved only inside that container are also deleted. However, the Docker image is not deleted because the image and container are separate. This shows why it is important to save important data using Docker volumes.

Containerization can also help developers and IT operations teams work together better. Developers can put their applications and needed files into containers, while IT operations teams can run those containers in different environments. This makes testing and deployment easier and helps reduce problems between development and production.

My GitHub portfolio is becoming a more organized record of my cloud computing activities. In this activity, I added Docker commands, documentation, screenshots, and a reflection. As I complete more laboratory activities, my portfolio will show the skills I have learned and the progress I have made in cloud computing.
