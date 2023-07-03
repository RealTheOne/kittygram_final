FROM python:3.9

WORKDIR /app

RUN apt-get update && apt-get install -y make

RUN pip install gunicorn==20.1.0

COPY requirements.txt ./

RUN pip install -r requirements.txt --no-cache-dir

COPY . .

CMD ["make", "run"]
# CMD ["gunicorn", "--bind", "0.0.0.0:9000", "kittygram_backend.wsgi"]