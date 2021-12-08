## Laravel 8 docker

### Setup
#### Containers up
```
docker-compose up -d
```
#### Access bash
```
docker-compose exec app-laravel bash
```
#### Install packages
```
composer install
```
#### Generate key
```
php artisan key:generate
```
#### Run migration
```
php artisan migrate
```
