hello-docker-django
==============================

A basic Django project running with Docker and PostgreSQL.

# Overview

This is a demo project for learning purposes only.
**Note:** The `settings.py` contains sensitive data and should not be used in production.

# Getting Started

Docker commands to get started.

```bash
docker-compose up --build -d

docker-compose exec web python manage.py makemigrations
docker-compose exec web python manage.py migrate
docker-compose exec web python manage.py createsuperuser

docker-compose down
```
