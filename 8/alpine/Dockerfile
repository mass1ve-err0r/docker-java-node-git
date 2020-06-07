FROM timbru31/java-node:8-alpine@sha256:55511261aa35ab08fe40bcd260a29abaccb7f069311cb27b43b0478fdb2be68a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
