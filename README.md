# Container for Laravel Artisian

Installs these php extensions and their dependencies.

 * gd
 * mcrypt

## Docker Compose
docker-compose.yml
```
...
artisan:  
      image: kahunacoder/docker-laravel-artisian
      volumes_from:
        - app
      links:
        - mysql
...

```

## Usage
List example using docker compose.
```
docker-compose run --rm artisan list
```