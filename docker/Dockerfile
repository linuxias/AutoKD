FROM nvidia/cuda:11.8.0-cudnn8-devel-ubuntu22.04

WORKDIR /app

COPY requirements.txt /app

RUN apt -y update
RUN apt -y install python3.10 python3-pip python-is-python3 jq wget curl
RUN pip install -r requirements.txt
