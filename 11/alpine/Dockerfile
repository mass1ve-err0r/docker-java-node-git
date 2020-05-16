FROM timbru31/java-node:11-alpine@sha256:885bd04a1b84288556af27ee456bfc77b8334a3f8a168e7a7246f981374d6813
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
