# Simplest Linux Docker

[![License](https://img.shields.io/badge/license-GPL-blue.svg)](https://raw.githubusercontent.com/hephaex/alpine-docker/master/LICENSE)
[![Docker Pulls](https://img.shields.io/docker/pulls/hephaex/alpine.svg)](https://hub.docker.com/r/hephaex/alpine-docker/)
[![Docker Stars](https://img.shields.io/docker/stars/hephaex/alpine.svg)](https://hub.docker.com/r/hephaex/alpine-docker/)

## Pull Docker Image
Pull the alpine image

> $ docker pull hephaex/alpine

## Check IP Address
Check IP Address of the container

> $ docker run hephaex/alpine ifconfig

## run bash shell
Launching a bash shell 

> docker run -i -t hephaex/alpine /bin/bash

## the container without stopping
Detaching from the container without stopping Ctrl-P Ctrl-Q

## Check the docker container
Check the docker container is still running

$ docker ps -a
