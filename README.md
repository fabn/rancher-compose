# Rancher Compose for Docker



[![Docker Stars](https://img.shields.io/docker/stars/fabn/rancher-compose.svg)](https://hub.docker.com/r/fabn/rancher-compose)
[![Docker Pulls](https://img.shields.io/docker/pulls/fabn/rancher-compose.svg)](https://hub.docker.com/r/fabn/rancher-compose)
[![ImageLayers Size](https://badge.imagelayers.io/fabn/rancher-compose:latest.svg)](https://hub.docker.com/r/fabn/rancher-compose)

This container can be used to run rancher compose commands.

## Quick Start

* Pass authentication variables to docker using env, e.g.

        docker run --rm -it -e "RANCHER_URL=<your-rancher-server>" -e "RANCHER_ACCESS_KEY=<your-access-key>" -e "RANCHER_SECRET_KEY=<your-secret-key>" \
          -v "$PWD:/workspace" fabn/rancher-compose
