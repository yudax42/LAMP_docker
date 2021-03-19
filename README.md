# LAMP_docker
docker-based LAMP stack (Linux, Apache, MySQL, PHP) with phpmyadmin
[dockerhub link](https://hub.docker.com/r/benaddayoussef/lampdocker)

![Lamp with docker](./lampwithdocker.jpg)

## Objective

Hosting web content in a linux environment.

## What is a LAMP stack?

A LAMP (Linux, Apache,MySQL,PHP) stack is free and open-source web stack used for hosting web content in a linux environment.

## What is Docker?

Docker is a container platform for applications. When ups can download pre-configured apps without the hassle of the installation and configuration process.

## How to use it ?

First install Docker in Your Machine From [Here](https://docs.docker.com/install/)

then Open Your terminal and type
```
docker run -it -v $PATH:/var/www/html -p 80:80 benaddayoussef/lampdocker:v2
```

**You replace $PATH with your working directory**

![runcontainer](./dockerruncontainer.jpeg)

after that you just type 
```
sh run.sh
```
![runapache](./runapache.jpeg)

to run script that start mysql and apache service 

Now just type localhost in your browser

![localhost](./website.jpeg)

the webserver works !

let's try php myadmin by typing localhost/phymyadmin

![phpmyadmin](./phpmyadmin.jpeg)

The username is **root** and the password is also **root**

![enterphpmyadmin](./phpmyadminworks.jpeg)

TADA!! phpmyadmin works without any problem

and finally to connect to mysql using your terminal your just type
```
mysql -u root -p
```
![connectmysqlfromterminal](./mysqlworksalso.jpeg)

By : actX3ng
