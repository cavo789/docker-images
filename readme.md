# Docker images

![Banner](./banner.svg)

# Installation

First, download [Docker Desktop](https://www.docker.com/products/docker-desktop) and run the installation.

Once done, make sure Docker is up and running. You'll see it by looking at the Docker icon in the Windows tray, near the clock.

## How to use

Open the folder with the image you want; f.i. `joomla` or `wordpress`. You'll there a file called `docker-compose.yml`.

Create a new folder on your disk and put the `docker-compose.yml` file there.

Start a DOS Prompt Session, go inside that folder and run these commands:

Run `docker-compose up -d` to load services. If you want, run `docker-compose ps` to see loaded services.

Surf to `http://localhost:8080/` to see the site and to `http://localhost:8081/` to open phpMyAdmin if you need it.

If you need to fill in credentials, use `admin` for the login and `admin` for the password.

You'll find other information's like the name of the database in the `docker-compose.yml` file.
