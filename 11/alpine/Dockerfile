FROM timbru31/java-node:11-alpine@sha256:e48b3346c9d438d426b5d2562656c7f5586f40bfb612dea9bf13ce0c935273ec
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
