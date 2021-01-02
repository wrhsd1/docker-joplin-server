# docker-joplin-server

[![Docker Build Status](https://img.shields.io/docker/cloud/build/florider89/joplin-server.svg)](https://hub.docker.com/r/florider89/smokeping-speedtest/) [![Docker Pulls](https://img.shields.io/docker/pulls/florider89/joplin-server.svg)](https://hub.docker.com/r/florider89/smokeping-speedtest/) [![Docker Automated build](https://img.shields.io/docker/cloud/automated/florider89/joplin-server.svg)](https://hub.docker.com/r/florider89/smokeping-speedtest/)

A Docker Image to run [Joplin Server](https://github.com/laurent22/joplin/tree/dev/packages/server).

![Joplin Server](https://p195.p4.n0.cdn.getcloudapp.com/items/L1uO8yx1/dc01a283-f2fc-453b-a504-61857ca9c663.png?v=82a88bf8a1e9119f9fa2a511ffe3c55a)

## Usage

The following `docker-compose.yml` will make Joplin Server available on 22300. There are 2 networks in the example below, one to talk to traefik and one between the Joplin Server and the Database.

## Tags

Currently there is only one version as there is no release yet for the server.

`latest`: regular builds of the `dev` branch. This will change to the latest release once available.

## Contribute

Feel free to contribute to this Docker image on [Github](https://github.com/flosoft/docker-joplin-server).