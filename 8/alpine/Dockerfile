FROM timbru31/java-node:8-alpine@sha256:0af0b24b0835b1a1303ae2112812ac663d08ce043393cbbbdbf138d7d9f1dc29
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
