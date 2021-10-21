# Node CI Docker images

Docker images for Node based on the [official Node Alpine images](https://hub.docker.com/r/_/node/).

These images contain the basic requirements for use with continuous integration in most projects.

## Images

|     | alpine | node    | size
| --- | :---:  | :---:   | :---:
| 14  | 3.14   | 14.18.1 | ![](https://img.shields.io/docker/image-size/adlacruzes/node-ci/14?style=square)
| 16  | 3.14   | 16.11.1 | ![](https://img.shields.io/docker/image-size/adlacruzes/node-ci/16?style=square)

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