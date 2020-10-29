FROM timbru31/java-node:11-alpine@sha256:7b8991f20b41d1b031493c91520ef10dc2d1178ee6a3832e9bc80f8f2af6a0ce
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
