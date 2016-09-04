# This repo is a fork of https://github.com/micahwedemeyer/automongobackup

The aim of this repo is to add docker container backup facility.

# v0.21

- Add Docker Container Facility

## How to work with Docker

This script allow you to make a dump in the host from a running mongo container, you just need to set __DOCKER_LINK__ and __DOCKER_CONTAINER__

```
DOCKER_LINK="db_1:mongo"
DOCKER_CONTAINER="mongo:3.3"
```

## License

This is released under GPL version 2.
