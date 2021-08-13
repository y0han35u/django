FROM python:latest

RUN apt-get update && apt-get install -y \
    tzdata \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /tmp/work

COPY requirements.txt ${PWD}

RUN pip install -r requirements.txt

ENV TZ=Asia/Tokyo

