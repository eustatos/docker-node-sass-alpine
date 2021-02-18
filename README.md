![Docker Image CI](https://github.com/eustatos/docker-node-sass/workflows/Docker%20Image%20CI/badge.svg)

# Description
Dockerfile which installs Node-SASS in an Alpine Linux image.

# Docker Hub
https://hub.docker.com/r/blairguk/node-sass-alpine/

# Pull image
docker pull blairguk/node-sass-alpine

# Run image
docker run blairguk/node-sass-alpine:<NODE_VERSION> node-sass-alpine

# Upgrade Node

* `docker build -t blairguk/node-sass-alpine:<NODE_VERSION> .`
* `docker push blairguk/node-sass-alpine:<NODE_VERSION>`
