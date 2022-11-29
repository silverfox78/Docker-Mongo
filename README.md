# Docker-Mongo

> Ejemplo de Docker-compose para disponer de una instancia de Mongo DB

![MongoDB](logo.png)


## TL:DR

> https://samuelbarrerabastidas.medium.com/mongo-con-docker-compose-78c57f790c92

## Imagenes oficiales de MongoDb

> https://hub.docker.com/_/mongo

## Repositorio Github

> https://github.com/silverfox78/Docker-Mongo.git

```sh
git init --initial-branch=main
git add .
git commit -am "Docker-Compose Mongo - Ejemplo practico"
git remote add origin https://github.com/silverfox78/Docker-Mongo.git
git pull --rebase origin main
git push origin main
```

## Validar compose

```sh
docker-compose --version
```

## Levantar imagen

```sh
docker-compose up -d
```

## Detener imagen

```sh
docker-compose stop
```

## Borrar imagen

```sh
docker-compose down
```