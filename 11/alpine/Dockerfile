FROM timbru31/java-node:11-alpine@sha256:1b3af4c6f3e641f0a0bfaf0bb6a632e6f6de5fcd519d1fbd1f0bbc533109e5b4
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
