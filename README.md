# Symfony-Docker

This is a test project for running a Symfony 4 project with Docker. It is based on the [Symfony Demo Application][1].

## Requirements

- Docker
- Docker-Compose

## Installation

1. `$ git clone git@github.com:thled/symfony-docker.git`
1. `$ cd symfony-docker`
1. Optional: Change ports, DB config etc in `.env` if you want to.
1. `$ docker-compose build`
1. `$ docker-compose up -d`

## Usage

- Open `localhost:80' in your browser. If you modified .env change the port accordingly.
- You can manage the DB with Adminer on `localhost:8080`.
- Load fixtures with `$ docker-compose exec php bin/console doctrine:fixtures:load`

[1]: https://github.com/symfony/demo
