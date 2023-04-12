# Curl Docker Image
Originally a fork of [pstauffer/docker-curl](https://github.com/pstauffer/docker-curl)

## Description
Small docker image with cURL and JQ based on [Alpine Linux](https://hub.docker.com/_/alpine/).

[![GitHub Workflow Status (branch)][github-actions-badge]][github-actions-link]

## Usage
```
docker run -it --rm --name curl ghcr.io/zenaptix-lab/curl
docker run -it --rm --name curl ghcr.io/zenaptix-lab/curl --version
docker run -it --rm --name curl ghcr.io/zenaptix-lab/curl https://ifconfig.co
```

## License
This project is licensed under `MIT <http://opensource.org/licenses/MIT>`.

[github-actions-badge]: https://img.shields.io/github/actions/workflow/status/zenaptix-lab/docker-curl/build.yml?branch=master "Github Workflow Status (master)"
[github-actions-link]: https://github.com/rblaine95/docker_monero/actions?query=workflow%3ADocker
