docker-registry-ui
==================

A simple web UI for browsing private docker registries

## Requirement

* python-flask
* python-dateutil

## Usage

Install a private docker registry and ```python run.py``` on the same server.

Browse to ```http://localhost:8080``` to begin using.

## Run as docker container
docker build -t anigeo/docker-registry-ui github.com/anigeo/docker-registry-ui
docker run -d -e REGISTRY_URL=<http://registry:5000> anigeo/docker-registry-ui

## Environment

* **REGISTRY_URL**
<br/>URL of private registry
<br/>Default: ```http://localhost:5000```

* **API_VERSION**
<br/>API version
<br/>Default: ```v1```

* **DEBUG**
<br/>Toggle debug mode
<br/>Default: ```False```
