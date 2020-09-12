FROM timbru31/java-node:8-alpine@sha256:8250d2636e9e2026570e03f3ca25d703ef651047a9892d1d817a0dafcc23ee07
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
