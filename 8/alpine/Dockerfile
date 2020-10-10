FROM timbru31/java-node:8-alpine@sha256:0a3db54cfb4644f0d1b8b3c2d65773e878e21821af22d07d797a4a5cbc5922bb
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
