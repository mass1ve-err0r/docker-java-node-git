FROM timbru31/java-node:8@sha256:9501809eba3d823f0f35c21f41d036ef9b25c411c16418696c14b7f1641032c1
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

SHELL ["/bin/bash", "-o", "pipefail", "-c"]

RUN apt-get update -qq \
 && apt-get install -qq --no-install-recommends git \
 && apt-get clean \
 && rm -rf /var/lib/apt/lists/*
