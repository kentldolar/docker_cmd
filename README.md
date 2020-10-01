# docker_cmd
list of common docker commands that I use

Vagrant + Virtualbox + Docker

Desc:
Vagrant  - To create automated VirtualBox OS
VirtualBox - Application to use
Docker - To create automated middleware installation and host security.


# docker build
docker build [OPTIONS] PATH | URL | 

# Docker cmd Execute sh container - Linux Base
docker exec -it <container-name> bash

# Show all running docker apps / images
docker ps
docker ps -a

# remove docker images
docker rm <docker-id>

# build docker-composer.yml
docker-compose up -d --build

# build docker-composer.yml and remove cache
docker-compose up -d --remove-orphans

# Show all running docker-compose apps / images
docker-compose ps

# stop running docker-compose apps / images
docker-compose stop

# log_timeout_error()
sudo pkill docker

# Source:
https://github.com/docker/compose/issues/3904

# docker delete all images
docker system prune -a --volumes

# docker nginx "413 Entiy too large"
https://qiita.com/takecian/items/639deeae094466de6546
client_max_body_size 20M;

# docker nginx 504 Gateway Time-out



# docker mysql "Incorrect format parameterエラー"
https://hara-chan.com/it/programming/incorrect-format-parameter-phpmyadmin/
https://techfree.jp/3147

# docker-compose.yml
volumes:
    - ./phpmyadmin-misc.ini:/usr/local/etc/php/conf.d/phpmyadmin-misc.ini

# phpmyadmin-misc.ini
allow_url_fopen = Off
max_execution_time = 600
memory_limit = 64M
post_max_size = 64M
upload_max_filesize = 64M

# End