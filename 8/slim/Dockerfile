FROM timbru31/java-node:8-slim@sha256:489abe705cf155a53382dd6a3a7737714478f306cee87b9e3917c56f457daac8
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

SHELL ["/bin/bash", "-o", "pipefail", "-c"]

RUN apt-get update -qq \
 && apt-get install -qq --no-install-recommends git \
 && apt-get clean \
 && rm -rf /var/lib/apt/lists/*
