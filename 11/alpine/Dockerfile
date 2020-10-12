FROM timbru31/java-node:11-alpine@sha256:e4f67a44668c31c7f4f5c07bbd8b3b29ba839bd6f2db3dcd6fa200f871467b6b
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
