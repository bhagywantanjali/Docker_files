DOCKER

Basic Docker Commands:

    docker run
        Use Case: To start a new container from an image.
        Example: docker run -d --name mycontainer nginx

    docker ps
        Use Case: To list running containers.
        Example: docker ps

    docker stop
        Use Case: To stop a running container.
        Example: docker stop mycontainer

    docker start
        Use Case: To start a stopped container.
        Example: docker start mycontainer

    docker restart
        Use Case: To restart a running container.
        Example: docker restart mycontainer

    docker rm
        Use Case: To remove a stopped container.
        Example: docker rm mycontainer

    docker images
        Use Case: To list available Docker images.
        Example: docker images

    docker pull
        Use Case: To download a Docker image from a registry.
        Example: docker pull ubuntu

    docker rmi
        Use Case: To remove a Docker image.
        Example: docker rmi ubuntu

    docker exec
        Use Case: To run a command inside a running container.
        Example: docker exec mycontainer ls /

    docker logs
        Use Case: To view logs of a container.
        Example: docker logs mycontainer

    docker inspect
        Use Case: To view detailed information about a container or image.
        Example: docker inspect mycontainer

    docker build
        Use Case: To build a Docker image from a Dockerfile.
        Example: docker build -t myimage .

    docker push
        Use Case: To push a Docker image to a registry.
        Example: docker push myimage

    docker tag
        Use Case: To tag a Docker image with a name.
        Example: docker tag myimage myregistry/myimage

    docker network create
        Use Case: To create a Docker network.
        Example: docker network create mynetwork

    docker volume create
        Use Case: To create a Docker volume.
        Example: docker volume create myvolume

    docker-compose up
        Use Case: To start services defined in a docker-compose.yml file.
        Example: docker-compose up -d

    docker-compose down
        Use Case: To stop and remove services defined in a docker-compose.yml file.
        Example: docker-compose down

    docker save
        Use Case: To save a Docker image to a tar archive.
        Example: docker save -o myimage.tar myimage

    docker pull
        Use Case: To download a Docker image from a registry.
        Example: docker pull nginx

    docker inspect
        Use Case: To display detailed information about a Docker container or image.
        Example: docker inspect mycontainer

    docker rename
        Use Case: To rename an existing Docker container.
        Example: docker rename oldname newname

    docker pause
        Use Case: To pause all processes within a running container.
        Example: docker pause mycontainer

    docker unpause
        Use Case: To resume all processes within a paused container.
        Example: docker unpause mycontainer

    docker top
        Use Case: To display the running processes of a container.
        Example: docker top mycontainer

    docker attach
        Use Case: To attach to a running container's standard input, output, and error streams.
        Example: docker attach mycontainer

    docker cp
        Use Case: To copy files or directories between a container and the local filesystem.
        Example: docker cp mycontainer:/app/file.txt .

    docker stats
        Use Case: To display a live stream of container resource usage statistics.
        Example: docker stats mycontainer

    docker history
        Use Case: To display the history of an image, including its intermediate layers.
        Example: docker history myimage

    docker port
        Use Case: To list the port mappings for a container.
        Example: docker port mycontainer

    docker logs
        Use Case: To fetch the logs of a container.
        Example: docker logs mycontainer

    docker commit
        Use Case: To create a new image based on the changes made to a container.
        Example: docker commit mycontainer myimage:v1

    docker events
        Use Case: To display real-time events from the Docker daemon.
        Example: docker events

    docker diff
        Use Case: To show the changes made to the filesystem of a container.
        Example: docker diff mycontainer

    docker pause
        Use Case: To pause all processes within a running container.
        Example: docker pause mycontainer

    docker exec
        Use Case: To execute a command within a running container.
        Example: docker exec -it mycontainer sh

    docker push
        Use Case: To push a Docker image to a registry.
        Example: docker push myimage

    docker save
        Use Case: To save a Docker image to a tar archive file.
        Example: docker save -o myimage.tar myimage

    docker load
        Use Case: To load a Docker image from a tar archive file.
        Example: docker load -i myimage.tar
