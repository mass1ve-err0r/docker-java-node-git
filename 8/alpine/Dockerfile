FROM timbru31/java-node:8-alpine@sha256:de94222461021fdda8addf655346727ce1cf933acbbe82bdaa090521cdca0315
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
