# ubuntu-docker-build

## Build a base container for Ubuntu Linux

`sudo docker build . -t ubuntu:0.0.1`

`sudo docker run --rm -it ubuntu:0.0.1`

## Use the base container to build a simple C++ application

`sudo docker build . -t hello-docker:1`

`sudo docker run --rm -it hello-docker:1`