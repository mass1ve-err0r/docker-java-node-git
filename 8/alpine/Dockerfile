FROM timbru31/java-node:8-alpine@sha256:14e4b756e3422de3549c30da2ca08f3dc34d67ffe87c0e278ee6251dcc3e649c
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
