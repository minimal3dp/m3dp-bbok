# Docker Commands

- `docker container ls` - list containers

- `docker stop <Container_ID>` - stop a container

- `docker rm <Container_ID>` - remove a stopped container

- `docker rm -f <Container_ID>` - force stop and remove a container

- `docker rmi -f <Image_name>` - remove an image

- `docker-compose up -d` - run the compose file

- `docker volume ls` - list volumes

- `docker volume rm [OPTIONS] VOLUME [VOLUME...]` - remove a volume

  

__Danger Commands:__

- `docker kill $(docker ps -q)` - stop all containers

- `docker rm $(docker ps -a -q)` - remove all containers

- `docker rmi $(docker images -q)` - delete all images

- `docker volume rm $(docker volume ls -q)` - delete all volumes