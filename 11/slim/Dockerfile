FROM timbru31/java-node:11-slim@sha256:178c47ea99b4db51f267a755aab22dfb93fa6058b159ced45940d58eef49f5cc
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
