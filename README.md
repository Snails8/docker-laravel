## install laravelX.X

```
$ make create-project # Install the latest Laravel project
$ make install-recommend-packages # Not required
```

or

```
$ docker-compose exec app bash

[app]

$ composer create-project --prefer-dist "laravel/laravel=8.*" .

$ php artisan -V 
Laravel Framework X.X.X
```
## version

php: 7.4-fpm-buster

composer: 1.10

nginx: 1.18-alpine

mysql: 8.0
