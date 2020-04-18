FROM timbru31/java-node:11-slim@sha256:c59c8dae1a9eb98e2f5d68d5ecad9913ac45316c3a4e84dd90f1aa9eae05cfd0
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

SHELL ["/bin/bash", "-o", "pipefail", "-c"]

RUN apt-get update -qq \
 && apt-get install -qq --no-install-recommends git \
 && apt-get clean \
 && rm -rf /var/lib/apt/lists/*
