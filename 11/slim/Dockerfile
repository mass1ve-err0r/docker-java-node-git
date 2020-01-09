FROM timbru31/java-node:11-slim@sha256:ae2de1201c74bd0844a0f3cbd5f6ddf87b5b91ebf037016b8e54a2a65a8dd34d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

SHELL ["/bin/bash", "-o", "pipefail", "-c"]

RUN apt-get update -qq \
 && apt-get install -qq --no-install-recommends git \
 && apt-get clean \
 && rm -rf /var/lib/apt/lists/*
