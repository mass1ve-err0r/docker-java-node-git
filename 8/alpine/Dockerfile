FROM timbru31/java-node:8-alpine@sha256:a069d8d51d4b8516df63fc198f1ae5a1a1418fcf37d55f4284c9729bf581f3d2
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
