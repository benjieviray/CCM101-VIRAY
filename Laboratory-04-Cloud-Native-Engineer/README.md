# Laboratory 04 – Cloud-Native Engineer

## Mission Overview

This laboratory activity focused on understanding cloud-native technologies, particularly the difference between Virtual Machines and Docker containers. The activity involved using Docker to pull and run an Nginx container and managing its lifecycle.

## Objectives

* Differentiate Virtual Machines and containers.
* Access and use Docker in a cloud-based environment.
* Execute basic Docker CLI commands.
* Pull and run an Nginx container.
* Manage the container lifecycle.
* Document the activity using Markdown.

## Docker Commands Executed

```bash
docker info
docker pull nginx
docker run -d --name nginx-server -p 8080:80 nginx
curl http://localhost:8080
docker ps
docker stop nginx-server
docker ps -a
docker rm nginx-server
docker ps -a
```

## Skills Learned

I learned how to use basic Docker commands to pull images, create and run containers, expose container ports, check running containers, stop containers, and remove containers. I also learned how to document Docker activities using Markdown.

## Challenges Encountered

One challenge I encountered was understanding that `-p 8080:80` is an option used with the `docker run` command and cannot be executed by itself. I also had to understand how host port 8080 connects to Nginx port 80 inside the container. Through the activity, I became more familiar with Docker commands and container management.
