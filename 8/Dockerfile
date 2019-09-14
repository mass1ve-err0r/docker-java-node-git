FROM timbru31/java-node:8@sha256:3b6bb843d96994d95a90ff93b7686fded8052c7365d00a46c2c6dece1d516ab0
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

SHELL ["/bin/bash", "-o", "pipefail", "-c"]

RUN apt-get update -qq && apt-get install -qq --no-install-recommends git=2.23.0 \
 && apt-get clean \
 && rm -rf /var/lib/apt/lists/*
