FROM timbru31/java-node:8-slim@sha256:29dff19986f5391abbc40c69dbbb26c9defa8ed3dea3c8d2420b022e66390ee6
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

SHELL ["/bin/bash", "-o", "pipefail", "-c"]

RUN apt-get update -qq && apt-get install -qq --no-install-recommends git
