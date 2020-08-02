FROM timbru31/java-node:8-alpine@sha256:e89fc67c121ec462dee49fdf15154a6da84496487ed7060aa8af607ab1aeabbc
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
