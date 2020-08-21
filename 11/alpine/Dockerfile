FROM timbru31/java-node:11-alpine@sha256:2ec55f02cf80f7b8fdc24ac5866dd41033938184c87c1d5ad6bb03f9ce0495a7
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
