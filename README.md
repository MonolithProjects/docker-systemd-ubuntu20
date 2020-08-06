# Ubuntu20 Ansible Test Image

[![GitHub Actions](https://github.com/MonolithProjects/docker-systemd-ubuntu20/workflows/Dockerfile%20test/badge.svg?branch=master)](https://github.com/MonolithProjects/docker-systemd-ubuntu20/actions)
[![DockerHub-layers](https://img.shields.io/microbadger/layers/monolithprojects/systemd-ubuntu20)](https://hub.docker.com/repository/docker/monolithprojects/systemd-ubuntu20)
[![DockerHub-pulls](https://img.shields.io/docker/pulls/monolithprojects/systemd-ubuntu20)](https://hub.docker.com/repository/docker/monolithprojects/systemd-ubuntu20)
[![DockerHub](https://img.shields.io/docker/cloud/automated/monolithprojects/systemd-ubuntu20?maxAge=2592000)](https://hub.docker.com/repository/docker/monolithprojects/systemd-ubuntu20)

Docker image with ubuntu20 and enabled systemd. Image contains also `ansible` user (UID/GID 1000) with NOPASSWD:ALL sudo rights.  
This docker image is ment to be used for development purpose. I do not recomend to use it in production.

## Tags

- `latest`  
- `<monthly build timestamp>` for the list of the tags see the [Docker Hub](https://hub.docker.com/repository/docker/monolithprojects/systemd-ubuntu20/tags?page=1)

## How-to

  1. Pull image with command `docker pull monolithprojects/systemd-ubuntu20:latest`  
  2. Run the container from the image: `docker run --detach --privileged --volume=/sys/fs/cgroup:/sys/fs/cgroup:ro monolithprojects/systemd-ubuntu20:latest`  

## License

MIT
