FROM timbru31/java-node:8-alpine@sha256:a9b112cac663d9c3ebbf00b54330c8f22e057f9fa6757096a0c91685599950d9
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
