# CHAMILO DEPLOYMENT

## CHAMILO PROJECT FOLDER

- Download zip or tar file of Chamilo proyect site - php7 version [Download Site](https://chamilo.org/en/download/)
- Uncrompress zip and rename directory to **chamilo/**
- Run command : `. permissions.sh`

## ENVIROMENT VARIABLES

- DOMAIN_APACHE_REAL
- DOMAIN_PHP_MYADMIN_REAL
- DOMAIN_APACHE_LOCAL
- DOMAIN_PHP_MYADMIN_LOCAL
- ALLOW_OVERRIDE **IS REQUIRED WITH VALUE TRUE**
- MYSQL_ROOT_PASSWORD
- MYSQL_DATABASE
- MYSQL_USER
- MYSQL_PASSWORD
- PMA_HOST
- EMAIL_CERBOT

## RUN DOCKER CONTAINERS

## TRAEFIK

- Run command `docker-compose -f docker-compose-traefik.yml up -d --build`

### RUN IN DEVELOPMENT MODE

- Run command
  `docker-compose up -d --build`

### RUN IN PRODUCTION MODE

- Run command `docker-compose -f docker-compose-production.yml up -d --build`

### INCLUDE

- Chamilo php7.2-apache
- Mysql 5.7
- Phpmyadmin

Development by **Ismael Cortegana**
