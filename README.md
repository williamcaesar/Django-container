# Django in a box#

Django apps running directly from a docker container

## Setup

Initial DB initialisation:

```
docker-compose run web python src/profiles_project/manage.py migrate
```
Image build:
```
docker-compose build
```
