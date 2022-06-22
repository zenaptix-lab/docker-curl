# Curl Docker Image
Originally a fork of [pstauffer/docker-curl](https://github.com/pstauffer/docker-curl)

## Description
Small docker image with cURL and JQ based on [Alpine Linux](https://hub.docker.com/_/alpine/).

![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/zenaptix-lab/docker-curl/Build/master)

## Usage
```
docker run -it --rm --name curl ghcr.io/zenaptix-lab/curl
docker run -it --rm --name curl ghcr.io/zenaptix-lab/curl --version
docker run -it --rm --name curl ghcr.io/zenaptix-lab/curl https://ifconfig.co
```

## License
This project is licensed under `MIT <http://opensource.org/licenses/MIT>`.
