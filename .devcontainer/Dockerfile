FROM ubuntu:22.04

RUN apt update && apt install -y \
    git build-essential scons m4 python3-dev python3-six \
    libprotobuf-dev protobuf-compiler libgoogle-perftools-dev \
    libboost-all-dev zlib1g-dev curl

WORKDIR /workspace
