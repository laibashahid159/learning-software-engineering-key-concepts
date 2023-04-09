## Docker

Docker is an open-source containerization platform that allows developers to create, deploy, and run applications in a portable and efficient way. Its also a social platform that allows people to share and find ralevant containers that might have something similar you can build on top off

### What are Containers

A Docker container is a lightweight, standalone executable package that contains everything needed to run an application, including the application code, libraries, dependencies, and runtime environment.

Here are some of the key things that a Docker container contains:

1. **Application code**: This is the code that makes up the application you want to run in the container.

2. **Dependencies**: These are the libraries, modules, and other software components that the application requires to run.

3. **Runtime environment**: This is the environment in which the application runs, such as the operating system, system libraries, and other system-level software.

4. **Configuration settings**: These are the settings that configure the application and the container, such as environment variables, network settings, and other options.

5. **File system**: The container has its own file system, which is isolated from the host file system and other containers.

6. **Network interfaces**: The container has one or more network interfaces that allow it to communicate with the host system and other containers.

7. **Storage**: The container can have one or more volumes that provide persistent storage for the application data.

Containers are designed to be portable and self-contained, which means that you can package an application into a container once and run it on any system that supports Docker, without worrying about compatibility issues or dependencies. This makes it easy to deploy and manage applications in a variety of environments, from local development to cloud-based production environments.

## Differences between Docker and Virtual Machines

Docker and virtual machines (VMs) are both used to create isolated environments for running applications, but they have different architectures and use cases. Here are the key differences between Docker and virtual machines:

1. Architecture: Docker is based on containerization technology, where applications are packaged into containers that share the host operating system kernel. Virtual machines, on the other hand, are based on virtualization technology, where a hypervisor creates virtual machines that run their own guest operating system.
2. Resource usage: Docker containers are more lightweight and efficient than virtual machines, as they share the host operating system kernel and only require the resources needed to run the application. Virtual machines, on the other hand, require a separate guest operating system and more resources to run.
3. Startup time: Docker containers can start up in seconds, compared to minutes for virtual machines.
4. Isolation: Docker containers provide less isolation than virtual machines, as they share the host operating system kernel and can potentially be affected by other containers on the same host. Virtual machines provide strong isolation between the guest operating system and the host operating system.
5. Portability: Docker containers can run on any system that supports Docker, without worrying about compatibility issues or dependencies. Virtual machines, on the other hand, are tied to the virtualization software and require a compatible hypervisor to run.
6. Management: Docker containers are easier to manage than virtual machines, as they can be easily created, run, and managed using Docker CLI or Docker Compose. Virtual machines require more configuration and management than Docker containers.

## Using Docker

- **Download Docker desktop and Install**
  Docker Desktop is a desktop application that provides an easy-to-use interface for developers to build, test, and deploy containerized applications.

- **Sign-up**
  sign up /sign in - it allows you pull or push any image available on docker hub

- **Test**
  you can test it by running the following code: `docker run hello-world`
  this will pull an image from docker hub that will print the information about docker

## Docker-Flow

![Docker Flow ](/statics/docker-flow.png "Docker Flow")
