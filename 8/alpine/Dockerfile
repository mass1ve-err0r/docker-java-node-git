FROM timbru31/java-node:8-alpine@sha256:2c8bb4a5a2e0d7a2523e24180143446fb5b8861c72a04c1577292518b70902be
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
