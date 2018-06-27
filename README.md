# Installation
## Work with docker
Make sure you have installed docker. You don't have to use exact same version with below.

```
$ docker -v
Docker version 18.03.1-ce, build 9ee9f40
$ docker-compose -v
docker-compose version 1.21.1, build 5a3f1a3
```

## How to start wordpress
```sh
$ docker-compose up -d
```

## How to restart
```sh
$ docker-compose restart
```

## How to check container status
```sh
$ docker-compose ps
```

## How to check logs
```sh
$ docker-compose logs -f # -f is option for follow mode
```
