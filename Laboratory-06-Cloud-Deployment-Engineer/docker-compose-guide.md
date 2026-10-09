# Docker Compose Guide

## What Does the `services:` Block Do?

The `services:` block defines the containers that make up the application. In this project, it defines two services: `database`, which uses the MariaDB image, and `app`, which uses the Nextcloud image. Docker Compose reads these definitions and manages the containers together.

## How Does Nextcloud Find the Database?

The environment variable `MYSQL_HOST=database` tells Nextcloud to connect to the database service named `database`. Docker Compose creates a shared network for the services, allowing the application container to resolve the database container using its service name.

## Difference Between `docker run` and `docker-compose up -d`

The `docker run` command starts an individual container using command-line options. Docker Compose uses a YAML configuration file to define and manage multiple related services, their settings, ports, and networks together.

The `-d` option runs the services in the background, allowing the terminal to be used for other commands.
