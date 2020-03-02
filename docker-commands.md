# Docker Commands

## docker info
* Gets basic information about Docker configuration
```bash
docker info
```


## docker pull <DOCKER-IMAGE-NAME>
* Use this command to download a specific Docker Image
```bash

```


## docker inspect
* Use this command to inspect specific Docker Image folder and file details
```bash
$ docker inspect <DOCKER-IMAGE-NAME>
```


## docker run
* This command creates a Container from the Image
* Command to Create the Container and runs in foreground
```bash
$ docker container run <DOCKER-IMAGE-NAME>
```
* Command to Create and Run the Container in background
```bash
$ docker container run -d <DOCKER-IMAGE-NAME>
```
* Assign a Name to a container
```bash
$ docker container run -d --name my_container <DOCKER-IMAGE-NAME>
```
* List all Docker Containers
```bash
docker container ls
```
* 
```bash
docker ps
```

## docker start
* This command creates a Container from the Image
```bash

```
