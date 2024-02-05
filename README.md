
# What is Docker?
Docker is an open-source containerization platform by which you can pack your application and all its dependencies into a standardized unit called a container.
Containers are light in weight which makes them portable and they are isolated from the underlying infrastructure and from each other container. 
You can run the docker image as a docker container in any machine where docker is installed without depending on the operating system.

Docker is popular because of the following:

1.Portability
2.Reproducibility
3.Efficiency
4.Scalability

# What is Dockerfile?
The Dockerfile uses DSL (Domain Specific Language) and contains instructions for generating a Docker image. 
Dockerfile will define the processes to quickly produce an image. While creating your application, you should create a Dockerfile in order since the Docker daemon runs all of the instructions from top to bottom.

# What is Docker Image?
It is a file, comprised of multiple layers, used to execute code in a Docker container. They are a set of instructions used to create docker containers. 
Docker Image is an executable package of software that includes everything needed to run an application.

# What is Docker Container?
Docker container is a runtime instance of an image. Allows developers to package applications with all parts needed such as libraries and other dependencies. 
Docker Containers are runtime instances of Docker images. Containers contain the whole kit required for an application, so the application can be run in an isolated way. 

# What is Docker Hub?
Docker Hub is a repository service and it is a cloud-based service where people push their Docker Container Images and also pull the Docker Container Images from the Docker Hub anytime or anywhere via the internet. Generally it makes it easy to find and reuse images. It provides features such as you can push your images as private or public registry where you can store and share Docker images.

### Some basic Docker commands are:
```
Docker run 
Docker ps 
Docker stop 
Docker rm 
Docker images 
Docker pull 
Docker exec 
Docker-compose 
Docker version
Docker search 
Docker restart 
Docker kill 
Docker login
Docker commit 
Docker push 
Docker network 
Docker history 
Docker copy
Docker logs   
Docker volume 
Docker logout 
```




