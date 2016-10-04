#Docker hints

Please visit ./docker_sample project if you want to check a working project

####Create a Dockerfile

[Dockerfile_Example](./docker_sample/Dockerfile)

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

####.dockerfile info

You need to add the files that you don't want to add direcly to the docker image, for example node_modules will be installed via the script `npm install` from the online npm repos