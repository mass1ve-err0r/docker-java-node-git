FROM timbru31/java-node:8-alpine@sha256:c84bac5e91d382940f6a092eb5c3f385b7cd79dfca95a3a6ad2679b573006eb3
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
