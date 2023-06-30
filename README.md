
# Educational project: CI / CD Kittygram project on a remote server
## Description:
Project kittygram_final is an educational project to get familiar with CI / CD of an app on a remote server.
It is a part of Python-developer course from Yandex-practicum.
This project allows you to post cards of cats with their photos, date of birth, color and some other info.

## Running project can be seen at:
https://yapkittygramtask.dynv6.net


## how to deploy
### Clone repository and access it through command line:
```
git clone git@github.com:RealTheOne/kittygram_final.git
cd kittygram_final
```
### Create and activate virtual environment:
```
cd backend
python3 -m venv venv
source venv/bin/activate
```
### Install requirements from requirements.txt:
```
python install -r requirements.txt
```
### Do migrations:
```
python manage.py migrate
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