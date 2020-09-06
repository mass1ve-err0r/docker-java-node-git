FROM timbru31/java-node:11-alpine@sha256:c9aebd08b9f74f29298920013639cc82e35e21c6ab7b6154a28e8950b30ac13e
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
