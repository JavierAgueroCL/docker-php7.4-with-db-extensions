[![Docker Hub; javieraguerocl/docker-php7.4-with-db-extensions](https://img.shields.io/badge/DOCKER%20HUB-javieraguerocl%2Fdocker--php7.4--with--db--extensions-blue?style=for-the-badge&logo=appveyor)](https://hub.docker.com/r/javieraguerocl/docker-nginx-php7.4+db-extensions/) [![nginx 1.19.10](https://img.shields.io/badge/nginx-1.19.10-brightgreen.svg?&logo=nginx&logoColor=white&style=for-the-badge)](https://nginx.org/en/CHANGES) [![php 7.4.1](https://img.shields.io/badge/php--fpm-7.4.1-blue.svg?&logo=php&logoColor=white&style=for-the-badge)](https://secure.php.net/releases/7_4_5.php) [![License MIT](https://img.shields.io/badge/license-MIT-blue.svg?&style=for-the-badge)](https://github.com/JavierAgueroCL/docker-php7.4-with-db-extensions/blob/master/Docker/LICENCE)

## Introduction
Docker Compose with Nginx, PHP7.4 + DB Extensions; MySQL, MongoDB, SQL Server (MSSQL)

## Building from source
To build from source you need to clone the git repo and run docker build:
```
$ git clone https://github.com/JavierAgueroCL/docker-php7.4-with-db-extensions.git
$ cd docker-php7.4-with-db-extensions
```

followed by
```
$ docker compose up
```


## Running
Copy the Git files in your Laravel (or something) proyect and run 
```
$ docker compose up
```

Default web root:
```
/var/www
```