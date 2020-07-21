FROM timbru31/java-node:11-alpine@sha256:3516cc7ba9bc722df51bbdbe8253b2d20b0daf7698e2c6dca8fe24c979ad7356
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
