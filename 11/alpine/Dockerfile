FROM timbru31/java-node:11-alpine@sha256:bf21f419aa5f43dbcf0f1ccf7d16e9f0d47bca4ebf3bf957a536f3e24eab560b
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
