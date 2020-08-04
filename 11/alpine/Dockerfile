FROM timbru31/java-node:11-alpine@sha256:b36311434d3ffcddf7ab4ef8a5f845b6de288cd307d5fb28ad4847eedfc4d949
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
