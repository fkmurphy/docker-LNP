# docker-LNP
Docker with Laravel, Nginx, PostgresSQL

# Instalar

```
$ git clone https://github.com/fkmurphy/docker-LNP.git
$ cd docker-LNP
$ submodule update --init --recursive
$ docker-compose up -d
$ docker exec -ti app sh
root-docker /app # composer install
root-docker /app # exit
```
