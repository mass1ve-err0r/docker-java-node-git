FROM timbru31/java-node:8@sha256:29aed6427b173978a66a7f9d58578d32198009df20410a387d5cf151fe21e97c
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

SHELL ["/bin/bash", "-o", "pipefail", "-c"]

RUN apt-get update -qq \
 && apt-get install -qq --no-install-recommends git \
 && apt-get clean \
 && rm -rf /var/lib/apt/lists/*
