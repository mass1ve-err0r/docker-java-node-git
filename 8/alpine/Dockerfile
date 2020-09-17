FROM timbru31/java-node:8-alpine@sha256:2268aae47a3d0f049ed272ef1198f12a534abbdb1d4e2d91f7098edacdd6a67e
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
