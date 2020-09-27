FROM timbru31/java-node:8-alpine@sha256:6c9d57d4eca313d340ebcff44868674fd4c2d561b918416cb3855179e7883b77
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
