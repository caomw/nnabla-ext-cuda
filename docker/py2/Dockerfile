FROM nvidia/cuda:8.0-cudnn6-runtime-ubuntu16.04

RUN apt-get update && apt-get install -y --no-install-recommends \
    python-pip python-setuptools python-wheel gcc python-dev \
    && rm -rf /var/lib/apt/lists/*

RUN pip install nnabla-ext-cuda
