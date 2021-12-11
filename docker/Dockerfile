FROM python:slim

RUN apt-get update \
 && apt-get install --no-install-recommends -y \
    git \
 && apt-get clean \
 && rm -r /var/lib/apt/lists/*
RUN pip install Django==3.2.9
