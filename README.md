# Docker MySQL Dev Image

Simple Docker image for MySQL development environment.

## Setup
```bash
docker build -t mysql-ready .
```

## Run
```bash
docker run -p 3306:3306 --env MYSQL_ROOT_PASSWORD=dev mysql-ready
```

## Build
docker build -t mysql-ready .