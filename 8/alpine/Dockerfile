FROM timbru31/java-node:8-alpine@sha256:22e056a094df760046b5f9b72a93d35297789b112de1e382e86ec74acaed4356
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
