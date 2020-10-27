FROM timbru31/java-node:8-alpine@sha256:e3f0b07c97891de1112e955ef06b5526d1f63bd33c948ad575a0ff4ffa8c1d84
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
