
# Project: CI / CD Kittygram project on a remote server (CI / CD Kittygram на удаленном сервере)
## Description:
Project kittygram_final is a project to implement CI / CD of an app on a remote server.
This project allows you to post cards of cats with their photos, date of birth, color and some other info.

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
