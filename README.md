## Launch Apache2 through the Docker and change "index.html"

* _Pull docker image from hub or create your own Dockerfile:_

`FROM ubuntu:16.04

RUN apt update && apt install -y apache2

EXPOSE 80/tcp`

* If you use your own Docker file then build it `docker build -t web`

* Run docker container using run-apache.sh script in repository 

* Change index.html at /var/www/html
