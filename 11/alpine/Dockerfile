FROM timbru31/java-node:11-alpine@sha256:e68ae862f1eb96dd59ca28a6e5ad5a52567b72d9a1d6ef3545253b1653437025
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
