FROM timbru31/java-node:11-alpine@sha256:f7cbd6d817c7190605865b1eab6a8410f2b8207c9c1efd5f5be348a07670a392
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
