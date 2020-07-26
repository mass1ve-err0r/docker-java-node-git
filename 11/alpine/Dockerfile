FROM timbru31/java-node:11-alpine@sha256:0185e0b1dd7367c9ebe857858e005b8eb681bb2297239014fd67c944b9e7e405
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
