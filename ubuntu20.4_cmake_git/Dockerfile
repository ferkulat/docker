FROM ubuntu:20.04

RUN apt update &&        \
    DEBIAN_FRONTEND=noninteractive apt-get install -y   \
    build-essential      \
    cmake                \
    git               && \
    apt autoremove -y && \
    apt clean -y

