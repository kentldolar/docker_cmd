# docker_cmd
list of common docker commands that I use

Vagrant + Virtualbox + Docker

Desc:
Vagrant  - To create automated VirtualBox OS
VirtualBox - Application to use
Docker - To create automated middleware installation and host security.


#docker build
docker build [OPTIONS] PATH | URL | 

#Docker cmd Execute sh container - Linux Base
docker exec -it <container-name> bash

#Show all running docker apps / images
docker ps
docker ps -a

#remove docker images
docker rm <docker-id>

#build docker-composer.yml
docker-compose up -d --build

#build docker-composer.yml and remove cache
docker-compose up -d --remove-orphans

#Show all running docker-compose apps / images
docker-compose ps

#stop running docker-compose apps / images
docker-compose stop

#log_timeout_error()
sudo pkill docker
#Source:
https://github.com/docker/compose/issues/3904

#docker delete all images
docker system prune -a --volumes
