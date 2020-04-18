FROM timbru31/java-node:8-alpine@sha256:d2cc66b8e8a2c0474decaeb5b81fe045df9a5bdbdf7df48985bb7cbd4c827c74
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
