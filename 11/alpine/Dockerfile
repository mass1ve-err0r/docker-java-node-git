FROM timbru31/java-node:11-alpine@sha256:36faa1fe0ef708cb4cef90cd3392576d46ea9508effb29bb21ee6486d9c923a4
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
