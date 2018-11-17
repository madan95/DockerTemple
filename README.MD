# Docker Project Template

Simple template for docker projects using db, phpmyadmin and traefik.

## Getting Started

Once you have the clone of the repo. Set the .env variables if you need to but it should work fine in your local development with current variables.

### Prerequisites

- Docker
- Docker-compose
- Make

### Installing

Create new network bridge named traffic.

```
cd traffic
make docker-start
```

Start Database

```
cd database
make docker-start
```

Start phpmyadmin

```
cd phpmyadmin
make docker-start
```

Creating Example Project (Wordpress)

```
cd example_project_1
make docker-start
```

## Running the tests

Now you should be able to access database with phpmyadmin on browser and access wordpress example project aswell.

### Example Project wordpress

- Go to https://wordpress.localhost and follow through wordpress installation process.
- Go to https://phpmyadmin.localhost and you should see the database for the wordpress that we created eariler

## Built with

- Docker (phpmyadmin/phpmyadmin, wordpress, mariadb, traefik)

## Versioning

We use [SemVer](https://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/madan95/dockerTemple/tags).


## Author
- Madan Limbu
