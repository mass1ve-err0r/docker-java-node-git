FROM timbru31/java-node:11-alpine@sha256:2f72c2565eeefd7d8c018a5f170a4b31026fb0a47319ba02ea69e33603383f3c
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
