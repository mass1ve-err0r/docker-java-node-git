FROM timbru31/java-node:11-alpine@sha256:dbd29d3f70edae9d2da4adadced8cd33ce20c2772048a762ef89b24b8e959420
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
