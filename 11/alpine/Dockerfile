FROM timbru31/java-node:11-alpine@sha256:82011481462169bf449d7cc9979a7fc49eeab1fe2820c405b52dd9d0d3978095
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
