
FROM jupyter/pyspark-notebook:latest


USER root

RUN pip install pyspark

RUN apt-get update && apt-get install -y postgresql-client

RUN chmod -R u+w /home/jovyan/data

COPY postgresql-42.5.0.jar /usr/local/spark/jars/


USER jovyan


