FROM timbru31/java-node:11@sha256:634844f9c6efebc5ca3240de34f7d87fdc8a9a663a2b7f2bf8128427cab61488
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

SHELL ["/bin/bash", "-o", "pipefail", "-c"]

RUN apt-get update -qq \
 && apt-get install -qq software-properties-common \
 && add-apt-repository ppa:git-core/ppa \
 && apt-get update -qq \
 && apt-get install -qq --no-install-recommends git=1:2.23.0-0ppa1~ubuntu19.10.1 \
 && apt-get clean \
 && rm -rf /var/lib/apt/lists/*
