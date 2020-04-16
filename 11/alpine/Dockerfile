FROM timbru31/java-node:11-alpine@sha256:7d698b3b63d5ee708a8d0083d7131fa1d95aac215f9988ec019c522f13fbfe32
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
