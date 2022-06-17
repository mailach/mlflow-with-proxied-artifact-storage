FROM continuumio/miniconda3:latest

RUN pip install mlflow  pymysql
RUN mkdir /mlartifacts

ADD . /app
WORKDIR /app

COPY wait-for-it.sh wait-for-it.sh 
RUN chmod +x wait-for-it.sh

