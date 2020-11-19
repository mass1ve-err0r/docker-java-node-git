FROM timbru31/java-node:8-alpine@sha256:6aa45c888cb621e4c92a9fb5500ab4226bcbc8649ae324ba9cf37384c4b4f3b5
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
