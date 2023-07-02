
# Educational project: CI / CD Kittygram project on a remote server
## Description:
Project kittygram_final is an educational project to get familiar with CI / CD of an app on a remote server.
It is a part of Python-developer course from Yandex-practicum.
This project allows you to post cards of cats with their photos, date of birth, color and some other info.

## Running project can be seen at:
https://yapkittygramtask.dynv6.net


## how to run project in dev-mode
### Clone repository and access it through command line:
```
git clone git@github.com:RealTheOne/kittygram_final.git
cd kittygram_final
```
### In command line run a command (You should have Docker and Docker Compose installed):
```
docker compose up
```
### collect Django static by a command:
```
docker compose exec backend python manage.py collectstatic
```
### Copy static:
```
docker compose exec backend cp -r /app/collected_static/. /static/static/
```
### In your browser open:
```
http://127.0.0.1:9000/
```

## stack
1. Python
2. Django
3. DRF
4. JWT + Djoser
5. NGinx
6. Gunicorn
7. React
8. Docker

## Author:
 Idrisov Arthur