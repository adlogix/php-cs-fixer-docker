# Php-cs-fixer docker image

Image used for running cs fixer on our ci server (https://cs.symfony.com/)

[![license](https://img.shields.io/github/license/adlogix/php-cs-fixer-docker.svg)]()

## Supported tags and respective `Dockerfile` links

* [`2.14.6`, `2.14`, `latest`](https://github.com/adlogix/php-cs-fixer-docker/blob/2.14.6/Dockerfile)
* [`2.13.3`, `2.13`](https://github.com/adlogix/php-cs-fixer-docker/blob/2.13.3/Dockerfile)
* [`2.12.8`, `2.12`](https://github.com/adlogix/php-cs-fixer-docker/blob/2.12.8/Dockerfile)

## Build command

    docker build -t adlogix/php-cs-fixer .

## Build an app

    docker run -ti --rm --volume=$(pwd):/srv -w /srv adlogix/php-cs-fixer
