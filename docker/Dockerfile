FROM ubuntu:22.04 as base

WORKDIR /opt
RUN apt-get update && apt-get install -y\
    vim neovim nano \
    git git-lfs \
    zip unzip \
    curl make build-essential xz-utils file tree \
    sudo \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /main

# java6
FROM openjdk:6-jdk-slim as java6


WORKDIR /main
