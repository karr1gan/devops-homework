FROM python:3.9-alpine

RUN pip install flask
RUN mkdir /var/app

COPY ./main.py /var/app

ENV FLASK_APP=main

CMD flask run