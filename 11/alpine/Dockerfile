FROM timbru31/java-node:11-alpine@sha256:0060c5bb4810ca20ea6bf725ec4c143c717f319a8d3f06faf00dad4fae9f8cd6
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
