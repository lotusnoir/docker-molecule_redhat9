# Docker Image with redhat8 base image 

This repo was created in order to test ansible roles with molecule.

## Build it locally

  docker build -t redhat9img .
  docker run --name redhat9con -d -P redhat9img
  docker exec -it redhat9con bash

## Use it from dockerhub

    https://hub.docker.com/repository/docker/lotusnoir/ansible_molecule_test_images:redhat9
