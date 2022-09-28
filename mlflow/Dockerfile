FROM continuumio/miniconda3:latest

RUN pip install mlflow 
RUN conda install psycopg2
RUN mkdir /mlartifacts

ADD . /app
WORKDIR /app

COPY wait-for-it.sh wait-for-it.sh 
RUN chmod +x wait-for-it.sh

