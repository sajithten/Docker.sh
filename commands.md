## To see the version of installed docker
```
Docker -v
```
## To run a sample hello-world in docker
```
docker run hello-world
```
## To list the images
```
docker images
```
## To see the running containers
```
docker ps
```
## To see all the containers/ stopped
```
docker ps -a
```
## To run the busybox shell in interactive terminal
```
docker run -it busybox sh
```
## To create a docker and forward to a particular port
```
docker run -d -p 80:80 docker/getting-started

curl http://127.0.0.1:80
```
## To start the container
```
docker start <container id>
```
## To restart the container 
```
docker restart <container id>
```
## To see the port mapping of a container
```
docker port <container id>
```
## To get the logs of particular container
```
docker logs <container id>
```
## To get the detail logs/inspect of container
```
docker inspect <ContainerID>
```
## To get the top process running in a container
```
docker top <Container ID>
```
## To enter into the executable / Shell of a particular container
```
docker exec -it <container ID> sh
```
## To pull an image from the dockerhub
```
docker image pull <image name>
```
## To build an image from a docker file
```
docker build -f <dockerfilepath>
```
## To build an image from the container
```
docker commit <container_name> <image_name>
```
## To tag a docker image
```
docker tag SOURCE_IMAGE<:Tag> TARGET_IMAGE<:Tag>
```
## To push an image to the docker hub
```
docker login && docker image push <image-name>
```
## To list the container images
```
docker images ls || docker images
```
