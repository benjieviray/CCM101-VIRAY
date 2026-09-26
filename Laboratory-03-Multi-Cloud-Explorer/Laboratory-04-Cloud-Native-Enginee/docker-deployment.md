# Docker Deployment

## Pull the Nginx Image

```bash
docker pull nginx
```

This command downloads the official Nginx image from Docker Hub.

## Run the Nginx Container

```bash
docker run -d --name nginx-server -p 8080:80 nginx
```

This command runs the Nginx container in detached mode. Port `8080` on the host is mapped to port `80` inside the container.

## Access Nginx

```bash
curl http://localhost:8080
```

This command accesses the Nginx web server through the mapped host port. The Nginx welcome page was displayed successfully.

## Container Lifecycle

### List Running Containers

```bash
docker ps
```

This command displays the currently running containers.

### Stop the Container

```bash
docker stop nginx-server
```

This command stops the running Nginx container.

### Verify the Container Status

```bash
docker ps
docker ps -a
```

These commands verify whether the container is still running and display stopped
