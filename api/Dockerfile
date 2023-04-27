FROM  python:3.8-slim-buster

ENV PYTHONUNBUFFERED=1

WORKDIR /api

RUN pip install django django-cors-headers

COPY . .

EXPOSE 8000