FROM timbru31/java-node:11-alpine@sha256:73d569fafbd17825e1d31e5c88a44bba715b68753fd998bd35e9c655316f0bce
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
