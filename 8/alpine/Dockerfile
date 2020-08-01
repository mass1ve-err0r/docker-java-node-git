FROM timbru31/java-node:8-alpine@sha256:f199e4243bee018c5792bbf3602fcbe1954397f20598fbd2f8ae2e0f2af7b9f2
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
