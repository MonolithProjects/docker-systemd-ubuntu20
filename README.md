# ubuntu20 Ansible Test Image

[![GitHub Actions](https://github.com/MonolithProjects/docker-systemd-ubuntu20/workflows/Dockerfile%20test/badge.svg?branch=master)](https://github.com/MonolithProjects/docker-systemd-ubuntu20/actions)
[![DockerHub-layers](https://img.shields.io/microbadger/layers/monolithprojects/systemd-ubuntu20)](https://hub.docker.com/repository/docker/monolithprojects/systemd-ubuntu20)
[![DockerHub-pulls](https://img.shields.io/docker/pulls/monolithprojects/systemd-ubuntu20)](https://hub.docker.com/repository/docker/monolithprojects/systemd-ubuntu20)
[![DockerHub](https://img.shields.io/docker/cloud/automated/monolithprojects/systemd-ubuntu20?maxAge=2592000)](https://hub.docker.com/repository/docker/monolithprojects/systemd-ubuntu20)

Ubuntu20 docker image (based on actual base image version). I am using it with Molecule for Ansible role testing.

## Tags

- `latest`: Latest version of the image

## How-to

  1. Pull image with command `docker pull monolithprojects/systemd-ubuntu20:latest`  
  2. Run the container from the image: `docker run --detach --privileged --volume=/sys/fs/cgroup:/sys/fs/cgroup:ro monolithprojects/systemd-ubuntu20:latest`  

## License

MIT
