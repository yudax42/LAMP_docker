# LAMP_docker
docker-based LAMP stack (Linux, Apache, MySQL, PHP) with phpmyadmin

![Lamp with docker](https://raw.githubusercontent.com/Benaddayoussef/LAMP_docker/master/lampwithdocker.jpg)

## Objective
Hosting web content in a linux environment.

## What is a LAMP stack?
A LAMP (Linux, Apache,MySQL,PHP) stack is free and open-source web stack used for hosting web content in a linux environment.

## What is Docker?
Docker is a container platform for applications. When ups can download pre-configured apps without the hassle of the installation and configuration process.

## How to use it ?
First install Docker in Your Machine (Docker installation) [https://docs.docker.com/install/]
Open
```
docker run -it -v $PATH:/var/www/html -p 80:80 benaddayoussef/lampdocker
```
**You replace $PATH with your working directory**

