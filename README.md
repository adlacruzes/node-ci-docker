# Node CI Docker images

[![Docker pulls](https://img.shields.io/docker/pulls/adlacruzes/node-ci?style=square)](https://hub.docker.com/r/adlacruzes/node-ci)

Docker images for Node based on the [official Node Alpine images](https://hub.docker.com/r/_/node/).

These images contain the basic requirements for use with continuous integration in most projects.

## Images

|     | alpine |  node   |                                                                 build                                                                 |                                       size                                       |
|-----|:------:|:-------:|:-------------------------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 14  |  3.15  | 14.19.1 | ![Github actions](https://github.com/adlacruzes/node-ci-docker/actions/workflows/node-14-docker-build-push.yml/badge.svg?branch=main) | ![](https://img.shields.io/docker/image-size/adlacruzes/node-ci/14?style=square) |
| 16  |  3.15  | 16.14.0 | ![Github actions](https://github.com/adlacruzes/node-ci-docker/actions/workflows/node-16-docker-build-push.yml/badge.svg?branch=main) | ![](https://img.shields.io/docker/image-size/adlacruzes/node-ci/16?style=square) |

## Usage

Images are available at https://hub.docker.com/r/adlacruzes/node-ci

Download image:

```
docker pull adlacruzes/node-ci:TAG
```

Run container:

```
docker run -it adlacruzes/node-ci:TAG sh -l
```
