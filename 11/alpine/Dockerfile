FROM timbru31/java-node:11-alpine@sha256:3d89904d53f5f69f7f9e2bff0fde37de9d3ae6443dae47c97d18d9e9f6539acf
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
