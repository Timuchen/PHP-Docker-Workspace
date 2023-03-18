# PHP Docker workspace

A simple initial build for a PHP project.

- PHP-FPM 8.2
- NGINX (latest)
- MySQL (8.0.32)
- PHPMyAdmin

Project directory: ./src
Web-site directory: ./src/public

## Quick start

- Open project directory: 'cd ./php_workspace'
- Add directories: 'mkdir ./docker/mysql/data && mkdir ./docker/nginx/logs'

## Docker comand helpers

- Run Docker workspase 'docker-compose up -d --build'
- Stop Docker workspase 'docker-compose down'
- View logs 'docker-compose logs --tal 25'
