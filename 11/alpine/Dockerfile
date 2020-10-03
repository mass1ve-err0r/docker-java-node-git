FROM timbru31/java-node:11-alpine@sha256:f81b22ec107b6a7dbc8e41bdf4096d4c7c60b9eb188181bf3b5e40c967a84760
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
