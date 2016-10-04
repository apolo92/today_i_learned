####Create a Dockerfile

    [Dockerfile_Example](./Dockerfile)

####Create image  

`docker build . -t <IMAGE_NAME>:<TAG_VERSION>`
`docker build . -t sample:0.1.2>`

####Run an image

`docker run -rm -it -p <HOST_PORT>:<DOCKER_PORT> <IMAGE_NAME>[:<TAG_VERSION>]`  
`docker run -rm -it -p 3000:3000 sample:0.1.2`  

####Show all Docker containers

`docker ps`

You can use grep to filter them

`docker ps | grep sample`

####To kill a container 

`docker kill <DOCKER_ID>`

####To list all docker images

`docker images`