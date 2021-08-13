# django
Just another Django project.

## Usage
```bash
#Build & Run
docker-compose up --build 

#Enter Docker container
docker-compose exec web /bin/bash

#Start Django project
django-admin startproject config .

#Start app
python3 manage.py startapp <app name>

#create admin
python3 manage.py createsuperuser

#DataBase migration
python3 manage.py makemigrations
python3 manage.py migrate

#Run server 
python3 manage.py runserver 0.0.0.0:8000
# you may need to add "0.0.0.0" to ALLOWED_HOSTS inside settings.py

#Stop docker container
docker-compose stop

```


