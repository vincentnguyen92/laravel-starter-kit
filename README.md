# Laravel Starter Kit

## How to build development environment
### Clone source code & Build docker
```
git clone git@github.com:vincentnguyen92/laravel-starter-kit.git laravel
cd laravel
docker-compose up -d
```
### Install packages via composer
```
docker-compose exec -u www-data php sh -c "composer install"
```

### Commands
- To stop all containers: `docker-compose down`
