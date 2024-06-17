# Docker Crash Course

Image -> Container(running image)

* Get base image from Docker Hub

## Build Image

`$ docker build -t appname[:tag] .`

## Run Image

`$ docker run --name myapp_c1 [--rm] -d -p 4000:4000 -v ./api:/app -v /app/node_modules myapp`

## Stop Container

`$  docker stop {container-name|container-id}`

## List All Containers

`$ docker ps -a`

## Restart Container

`$ docker start {container-name|container-id}`

## List All Images

`$ docker images`

## Remove Image

`$ docker {rmi|image remove} {image-id|image-name} [-f]`

## Remove Stopped Containers

`$ docker {container rm|rm} {container-name|container-id}`

## Remove All Images, Containers, & Volumes

`$ docker system prune -a`

## Docker Compose

### Start

`$ docker compose up -d`

### Stop

`$ docker compose down`

## YouTube

1. What is Docker?
2. Installing Docker
3. Images & Containers
4. Parent Images & Docker Hub
5. The Dockerfile
6. dockerignore
7. Starting & Stopping Containers
8. Layer Caching
9. Managing Images & Containers
10. Volumes
11. Docker Compose
12. 
13. 