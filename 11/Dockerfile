FROM timbru31/java-node:11@sha256:0353e0d57ec7a2f5bba07fddd9a0f6ca943410c65a673746f1f990068fc2be5a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

SHELL ["/bin/bash", "-o", "pipefail", "-c"]

RUN apt-get update -qq \
 && apt-get install -qq --no-install-recommends git \
 && apt-get clean \
 && rm -rf /var/lib/apt/lists/*
