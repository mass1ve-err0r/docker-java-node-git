FROM timbru31/java-node:8@sha256:37eb66a8302bd24f68556da1db36844955d724793a4f236b098b4a40b10bdf80
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

SHELL ["/bin/bash", "-o", "pipefail", "-c"]

RUN apt-get update -qq \
 && apt-get install -qq --no-install-recommends git \
 && apt-get clean \
 && rm -rf /var/lib/apt/lists/*
