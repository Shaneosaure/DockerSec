# DockerSec: Cybersecurity Training and Testing Environment
This repository contains all of the necessary file of our Project "DockerSec". This project aims to create a virtualized environment to test configurations and to train in cybersecurity (especially pentesting).
Docker being the main technology used for this project, we aim to facilitate and reduce the performances requirements of such environemment deployments. In comparison with a usual setup of 6 VMs in VMware/Virtualbox, we provide a single `docker-compose.yml`, preconfigured and to simply start!

# Getting started (work in progress)
To start the project, simply download the docker-compose.yml provided and run the following:
```shell
$ docker compose up -v
```
We used docker-compose v2, we do not support docker-compose v1 (click [here](https://docs.docker.com/compose/migrate/#what-are-the-differences-between-compose-v1-and-compose-v2) to read more about compose v1 & v2)

# External dependencies (work in progress)
For the moment none (17/10)

# Build dependencies (work in progress)
We have provided each of the docker images in two formats:
* Dockerfile: you can build the images on local and tweak them
* DockerHub: premade images already on the cloud, simply have to download them
By default, we use the DockerHub images, but you can change for the Dockerfile like [follow](https://docs.docker.com/engine/reference/commandline/build/)

# Run dependencies (work in progress)
For the moment none (17/10)

# Authors
* Rémi JARDRET - network referent - ethical hacker
* Stéphane SIMON - docker referent - ethical hacker

# License (work in progress)
None settled for the moment (17/10)
