# learning

## build docker image

```bash
docker build -t checkiamsiam/dockerize-nodejs-server .
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
docker run -p 5000:3000 checkiamsiam/dockerize-nodejs-server:latest
```

## rebuild docker image

```bash
docker build -t checkiamsiam/dockerize-nodejs-server:another-tag-name .
```
