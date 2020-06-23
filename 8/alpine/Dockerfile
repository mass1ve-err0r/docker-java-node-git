FROM timbru31/java-node:8-alpine@sha256:4574a9657f18ff288c899000fdc186d59f814070f0d388dfd7e4d517552095c4
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
