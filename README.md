# MarelloCommerce Docker Image
[![GitHub Tag](https://img.shields.io/github/tag/djocker/marellocommerce.svg)](https://hub.docker.com/r/djocker/marellocommerce/tags/) 
[![Layers](https://images.microbadger.com/badges/image/djocker/marellocommerce.svg)](https://microbadger.com/images/djocker/marellocommerce "Get your own image badge on microbadger.com") 
[![Docker Pulls](https://img.shields.io/docker/pulls/djocker/marellocommerce.svg)](https://hub.docker.com/r/djocker/marellocommerce/) 
[![Build Status](https://travis-ci.org/djocker/marellocommerce.svg?branch=master)](https://travis-ci.org/djocker/marellocommerce)

The docker image with source code of MarelloCommerce application.
This image is used as part of docker stack (see compose configs).

## Requirements

1. [Docker](https://www.docker.com/)
2. [Docker Compose](http://docs.docker.com/compose)

## Usage

### MarelloCommerce stack with automated installation

Run containers in attached mode

```
$ docker-compose -f docker-compose-auto.yml up
```

Run containers in detached mode

```
$ docker-compose -f docker-compose-auto.yml up -d
```

_Navigate to [http://localhost:3080](http://localhost:3080) or [http://localhost:3080/admin](http://localhost/admin:3080) in your web browser (default admin login/password: admin / admin1111)_

Stop containers

```
$ docker-compose -f docker-compose-auto.yml stop
```

Remove containers

```
$ docker-compose -f docker-compose-auto.yml down
```

### MarelloCommerce stack with web installation

Run containers in attached mode

```
$ docker-compose -f docker-compose.yml up
```

Run containers in detached mode

```
$ docker-compose -f docker-compose.yml up -d
```

Navigate to [http://localhost:3080](http://localhost:3080) in your web browser, and install application via web wizard

Stop containers

```
$ docker-compose -f docker-compose.yml stop
```

Remove containers

```
$ docker-compose -f docker-compose.yml down
```
