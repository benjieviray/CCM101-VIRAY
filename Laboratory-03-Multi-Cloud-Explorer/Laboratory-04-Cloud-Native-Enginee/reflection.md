# Mission Reflection

This laboratory activity helped me understand the difference between Docker containers and Virtual Machines. A Docker container can start much faster than installing and booting a complete operating system on a Virtual Machine. In this activity, I was able to pull the Nginx image and run a web server using only a few Docker commands. This showed me how containers can make application deployment faster and more efficient.

The port mapping `-p 8080:80` is necessary because it connects a port on the host machine to the port inside the container. Nginx uses port 80 inside the container, while port 8080 on the host allows me to access the web server through `http://localhost:8080`. Without this port mapping, I would not be able to access the Nginx web server through the host's port 8080.

When the `docker rm` command is used, the specified container is removed completely after it has been stopped. Any data stored only inside the container can be lost when the container is removed. This shows why persistent data should be stored using appropriate Docker storage options when necessary.

Containerization can also change how software developers and IT operations teams work together. Developers can package applications and their required dependencies into containers, while IT operations teams can deploy those containers consistently in different environments. This can make the development and deployment process more organized and collaborative.

My GitHub portfolio is also evolving as I add more laboratory activities and technical documentation. This laboratory adds practical experience with Docker, Nginx, port mapping, container management, and Markdown documentation. The screenshots provide evidence of the commands and results I completed during the activity.
