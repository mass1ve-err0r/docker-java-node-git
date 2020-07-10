FROM timbru31/java-node:8-alpine@sha256:0d258c7ca3a4adc3316881ddd10e9ca459b6a8ed5c909a9025aa183fb9556a46
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
