# Adminer Docker Container Image

- from [wodby/adminer](https://github.com/wodby/adminer)

[![Build Status](https://github.com/wodby/adminer/workflows/Build%20docker%20image/badge.svg)](https://github.com/wodby/adminer/actions)
[![Docker Pulls](https://img.shields.io/docker/pulls/wodby/adminer.svg)](https://hub.docker.com/r/wodby/adminer)
[![Docker Stars](https://img.shields.io/docker/stars/wodby/adminer.svg)](https://hub.docker.com/r/wodby/adminer)
[![Docker Layers](https://images.microbadger.com/badges/image/wodby/adminer.svg)](https://microbadger.com/images/wodby/adminer)

## Docker Images

❗For better reliability we release images with stability tags (`wodby/adminer:4.8-X.X.X`) which correspond to [git tags](https://github.com/wodby/adminer/releases). We strongly recommend using images only with stability tags. 

Overview:

- All images based on Alpine Linux
- Base image: [wodby/php](https://github.com/wodby/php)
- [GitHub actions builds](https://github.com/wodby/adminer/actions)  
- [Docker Hub](https://hub.docker.com/r/wodby/adminer)

Supported tags and respective `Dockerfile` links:

- `4.8`, `4`, `latest` [_(Dockerfile)_](https://github.com/wodby/adminer/tree/master/Dockerfile)

Plugin loader scripts used from [TimWolla/docker-adminer](https://github.com/TimWolla/docker-adminer).

## Environment Variables

| Variable                    | Default Value | Description                                             |
| --------------------------- | ------------- | ------------------------------------------------------- |
| `ADMINER_DEFAULT_DB_DRIVER` | `server`      | `server` is the same as `mysql`, `pgsql` for PostgreSQL |
| `ADMINER_DEFAULT_DB_HOST`   |               |                                                         |
| `ADMINER_DEFAULT_DB_NAME`   |               |                                                         |
| `ADMINER_DESIGN`            |               | Adminer theme, e.g. `nette`                             |
| `ADMINER_PLUGINS`           |               | Separated by space, e.g. `tables-filter tinymce`        |
| `PHP_CLI_MEMORY_LIMIT`      | `512M`        |                                                         |
| `PHP_MAX_EXECUTION_TIME`    | `0`           |                                                         |
| `PHP_POST_MAX_SIZE`         | `512M`        |                                                         |
| `PHP_UPLOAD_MAX_FILESIZE`   | `512M`        |                                                         |

See [wodby/php](https://github.com/wodby/php) for all variables

## Deployment

Deploy Adminer to your own server via [![Wodby](https://www.google.com/s2/favicons?domain=wodby.com) Wodby](https://wodby.com).
