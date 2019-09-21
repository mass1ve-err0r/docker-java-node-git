FROM timbru31/java-node:11-alpine@sha256:38c6f7cdf2f36e6c3ae07b967c896425d87864d0f8ce28f182cd8d1b7c615a41
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
