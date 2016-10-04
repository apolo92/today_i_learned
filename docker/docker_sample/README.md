##A sample of a Docker App

First install Docker 12.x

Then create the image with the Dockerfile

`docker build . -t docker_sample:1.0.0`  

`docker run -rm -it -p 3000:3000 docker_sample:1.0.0`  

Now you can check this server on your browser: http://localhost:3000