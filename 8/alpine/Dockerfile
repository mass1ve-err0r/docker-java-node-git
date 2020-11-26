FROM timbru31/java-node:8-alpine@sha256:9535025457a08d16ba13a6e0cb440fda0a0e489010b8438461a33c3b025dcef1
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
