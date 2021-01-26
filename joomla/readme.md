# Joomla

## Introduction

Start a Joomla site in a Docker container.

## Step by step

1. Create a new folder and put the `docker-compose.yml` file in that folder.
2. Run `docker-compose up -d` to load services. If you want, run `docker-compose ps` to see loaded services.

Surf to `http://localhost:8080/` to see the site and to `http://localhost:8081/` to open phpMyAdmin if you need it.

## Volumes

* The site will be stored in the `./site` folder
* The database will be stored in the `./db` folder.

## Other information's

* database name: `joomla`
* login: `admin`
* password: `admin`
