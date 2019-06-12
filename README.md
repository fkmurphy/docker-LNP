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
docker-laravel /app $ composer install
docker-laravel /app $ cp .env.example .env
docker-laravel /app $ php artisan key:generate
docker-laravel /app $ exit 
```

