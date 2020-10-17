FROM timbru31/java-node:8-alpine@sha256:246afe9805c9c22ada3985e6171da41bb3f799dba0a575b8c848c8e5a8f33c5c
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
