# DOCKER PROJECT

**I HAVE DONE OUR DOCKER TRAINING UNDER MR. VIMAL DAGA.I HAVE CREATED MY PROJECT USING JOOMLA AND MYSQL ON LINUX.**

# ABOUT DOCKER

**Docker is basically a container engine which uses the Linux Kernel features like namespaces and control groups to create containers on top of an operating system and automates application deployment on the container. It provides a lightweight environment to run your application code.**

# DOCKER COMPOSE

**Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application's services. Then, with a single command, you create and start all the services from your configuration. ... Run docker-compose up and Compose starts and runs your entire app.**
# PREREQUISITES

**FISRT YOU SHOULD HAVE DOCKER AND DOCKER-COMPOSE IN YOUR SYSTEM .THEN YOU SHOULD INSTALL JOOMLA IMAGE AND MYSQL IMAGE IN LINUX TERMINAL. YOU SHOULD ALSO INSTALL MYSQL SERVER.FOR INSTALLING MYSQL YOU SHOULD USE YUM COMMAND.FIRST U HAVE TO CONFIGURE YUM THEN AFTER U CAN USE YUM COMMAND**
```
docker pull joomla
docker pull mysql
yum install mysql
```

# SET-UP FOR CODE

**AFTER THIS MAKE A DIRECTORY USING **
```
mkdir myproject
vim docker-compose.yml
```
**EXTENSION SHOULD YML ONLY**
**WRITE THE CODE IN docker-compose.yml file**

**RUN YOUR CODE**

**THEN RUN YOUR CODE BY**
```
docker-compose up
```
**AND FOR STOPING IT USE COMMAND**
```
docker-compose stop/down
```
