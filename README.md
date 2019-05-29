# docker-LNP
Docker with Laravel, Nginx, PostgresSQL

# Instalar

```
$ git clone https://github.com/fkmurphy/docker-LNP.git
$ cd docker-LNP
$ submodule update --init 
$ cp example.env .env
$ docker-compose up -d --build
$ docker exec -ti app sh
root-docker /app # composer install
root-docker /app # exit
$ docker exec app php artisan key:generate
```

