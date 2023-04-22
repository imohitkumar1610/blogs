---
title: "Getting Started with Docker:
A Beginner's Guide to Docker and its Commands"
seoTitle: "Getting started with Docker: A beginners guide to Docker."
datePublished: Sun Apr 16 2023 08:03:00 GMT+0000 (Coordinated Universal Time)
cuid: clgj4dr1v000n09iehv6d6p48
slug: getting-started-with-docker-a-beginners-guide-to-docker-and-its-commands
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1681631700969/4e241376-6a2b-4f7e-9885-d125163bf94d.jpeg
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1681632074178/a975115f-c2c3-480b-91b6-2474e88701f7.webp
tags: docker, opensource, devops, containers, docker-images

---

Docker is a powerful tool that allows developers to create, deploy, and run applications in containers. These containers are like virtual machines but are more lightweight and portable. With Docker, you can package your applications and their dependencies into a single container, making deploying your application across different environments easy.

In this guide, we will cover the basics of Docker and its commands to help you get started with this powerful tool.

# What is Docker?

Docker is an open-source platform that allows developers to build, package, and deploy applications in containers. Containers are a lightweight way to package an application with all its dependencies, allowing it to run consistently across different environments.

Docker uses a client-server architecture, where the Docker client communicates with the Docker daemon, which is responsible for building, running, and managing containers. Docker containers are isolated from each other and from the host system, making them a secure and efficient way to run applications.

## Docker Commands

Here are some of the most common Docker commands that you will need to know to get started:

**docker run**

The `docker run` command is used to run a container.

```bash
docker run hello-world
```

This command will run the **Hello World** container, which is s simple text image that verifies whether the docker is installed and working properly or not.

# How?

Now the question is How docker runs a container and prints hello world on the screen? This question has a pretty simple answer the docker will first look into the local system whether it has any image names hello-world or not, if the image is not present locally then it would go to the **Docker Hub** and pulls the image named hello-world and runs it in the system.

**docker build**

The `docker build` command is used to build a Docker image from a Docker file. Here's an example:

```bash
docker build -t my-image
```

**Docker File** is a text document that consists of all the commands a user could on the command line to assemble an image.

This command will build a Docker image based on the Dockerfile in the current directory and tag it with the name `my-image`.

**docker image**

The `docker images` command is used to list all the Docker images that are currently installed on your system.

```bash
docker image
```

**docekr ps**

The `docker ps` command is used to list all the Docker containers that are currently running on your system.

```bash
docker ps
```

**docker stop**

The `docker stop` command is used to stop a running container.

```bash
docker stop my-container
```

This command will stop the container with the name `my-container`.

**docker rm**

The `docker rm` command is used to remove a container.

```bash
docker rm my-container
```

This command will remove the container with the name `my-container` .

# conclusion

Docker is a powerful tool that can help you build, package, and deploy applications in containers. In this guide, we covered the basics of Docker and some of its most common commands. With this knowledge, you can start exploring Docker and its many features.

# Thank You!!