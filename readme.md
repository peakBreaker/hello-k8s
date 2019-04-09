# Learning k8s

This repo is my notes and interpretation of how to get a project up and running
on kubernetes in google cloud, and should serve as a reference to myself.

## App

The repo contains a simple webapp in the app directory.  This webapp is
dockerized. `cd` into the app dir and build the docker container using the 
following command:

`$ docker build -t hello_k8s:latest .`

Run the docker container:

`$ docker run -p 80:8000 --rm hello_k8s:latest`

Then go to localhost and you should see hello world served from the container

![hello_world_container](./hello_world.png)


## Running on minikube

## K8s cluster on gcloud

### Setup on gcloud

### Deploy the app
