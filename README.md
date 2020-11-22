# sopo_1

# Launch Apache2 through the Docker and change index.html

## 1. Pull docker image from hub or create your own Dockerfile:

For example:

FROM ubuntu:16.04

RUN apt update && apt install -y apache2

EXPOSE 80/tcp

## 2. Run docker container using run-apache.sh script in repository 

## 3. Change index.html at /var/www/html

Result:

![Image of index](https://pastenow.ru/cd9ed1ad8ce561dbab2681d08a0efaf8)
