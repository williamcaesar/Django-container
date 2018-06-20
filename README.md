# Django in a box

Django apps running directly from a docker container

## Setup

With your Django project inside src/core/ do:

Initial DB initialisation:

```
docker-compose run web python src/profiles_project/manage.py migrate
```
Container build and run:
```
docker-compose build
docker-compose up
```
---
you can pull the image with:

```
docker pull williamcaesar/django-container
```

