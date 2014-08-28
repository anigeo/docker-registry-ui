docker-registry-ui
==================

A simple web UI for browsing private docker registries

## Requirement

* python-flask
* python-dateutil

## Usage

Install a private docker registry and ```python run.py``` on the same server.

Browse to ```http://localhost:8080``` to begin using.

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
