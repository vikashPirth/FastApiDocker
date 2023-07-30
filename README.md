# FastApiDocker
A basic example to make a docker image of fast API

# Command to build the image
docker build -t iamge-name:latest .

# Command to create the container from docker image 
docker run --name container-name  -d -p 3001:80 image-name:latest

# Running an Interactive Shell in a Docker Container
docker exec -it docker-id  /bin/bash


