# learning docker

## build docker image

```bash
docker build -t checkiamsiam/dockerize-nodejs-server .
```

## See docker images

```bash
docker images
```

## rebuild docker image

```bash
docker build -t checkiamsiam/dockerize-nodejs-server:another-tag-name .
```

## push docker image

```bash
docker push checkiamsiam/dockerize-nodejs-server:latest
```

## pull docker image

```bash
docker pull checkiamsiam/dockerize-nodejs-server:latest
```

## run docker image from docker hub

```bash
docker run -p 5000:3000 -d checkiamsiam/dockerize-nodejs-server:latest
```

## running docker containers

```bash
docker ps -a
```

## stop docker container

```bash
docker stop <container id>
```

## remove docker container

```bash
docker container rm <container id>
```

## remove docker image

```bash
docker image rm <image id>
```

## remove all docker images and containers

```bash
docker system prune -a
```
