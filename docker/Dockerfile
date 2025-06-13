FROM perl:latest

COPY . /openkore

RUN apt-get update && \
    apt-get install -y --no-install-recommends \
    git \
    python-is-python3 \
    build-essential \
    cpanminus \
    libreadline-dev \
    libncurses-dev \
    libssl-dev \
    libz-dev \
    libcurl4-openssl-dev

WORKDIR /openkore
