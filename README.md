# django-recipe-api

1. Build with docker compose `docker-compose build`


# Helpful command 
Django project created through docker-compose after build 
`docker-compose run app sh -c "django-admin startproject app ."`
Core app created
`docker-compose run app sh -c "python manage.py startapp core"`
To run unit test
`docker-compose run app sh -c "python manage.py test"`