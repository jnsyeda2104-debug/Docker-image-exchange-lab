# Docker Image Exchange Lab

## Project Overview

This project demonstrates the fundamentals of Docker and the process of exchanging Docker images between users.

The lab focuses on understanding Docker images and containers, verifying Docker installation, running containers, and working with a shared Docker image through Docker Hub.

## Objectives

- Understand the difference between Docker images and containers.
- Install and verify Docker.
- Run the official Hello World container.
- Work with Docker Hub images.
- Pull and run a shared Docker image.
- Create and manage Docker containers.
- Understand port mapping and container execution.

## Technologies & Tools

- Docker
- Docker Hub
- Docker Desktop
- PowerShell
- Windows

## Practical Tasks Performed

### 1. Docker Installation Verification

Verified Docker installation using:

```bash
docker --version
```

Docker version used: `29.8.2`

### 2. Running Hello World

Executed the official Docker test image:

```bash
docker run hello-world
```

The successful output confirmed that Docker was installed and working correctly.

### 3. Docker Image Exchange

Worked with the shared Docker image:

```bash
jnsyeda/friend-exchange:latest
```

### 4. Running a Container

Removed an existing container and launched a new container using:

```bash
docker rm -f friend-container-2
```

```bash
docker run -d --name friend-container-2 -p 8080:80 jnsyeda/friend-exchange:latest
```

This command runs the container in detached mode and maps port 8080 on the host to port 80 inside the container.

## Screenshots & Evidence

Terminal screenshots documenting Docker installation, Hello World execution, image exchange, and container management are included in the repository's `screenshots` folder.

## Key Learning Outcomes

- Understanding Docker fundamentals.
- Working with Docker images and containers.
- Using Docker Hub to share images.
- Pulling and running shared images.
- Managing containers through PowerShell.
- Understanding Docker port mapping.
- Gaining practical experience with containerization.

## Author

**Syeda Jovaria Nisar**

AI & Machine Learning Learner
