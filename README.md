# Nginx for Laravel Docker Container Image 

Overview:

* All images are based on Alpine Linux
* Base image: [wodby/php-nginx](https://github.com/wodby/php-nginx)
* [Docker Hub](https://hub.docker.com/r/tomcat2111/laravel-nginx)

[_(Dockerfile)_]: https://github.com/staegi/docker-laravel-nginx/tree/master/Dockerfile

## Environment Variables

See more at [wodby/php-nginx](https://github.com/wodby/php-nginx)

| Variable                           | Default Value     | Description |
| ---------------------------------- | ----------------- | ----------- |
| `NGINX_BACKEND_HOST`               |                   |             |
| `NGINX_SERVER_EXTRA_CONF_FILEPATH` | `/var/www/public/`|             |
| `NGINX_SERVER_NAME`                | `laravel`         |             |
| `NGINX_SERVER_ROOT`                | `/var/www/public` |             |

## Orchestration Actions

See [wodby/nginx](https://github.com/wodby/nginx) for all actions.
