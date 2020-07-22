FROM timbru31/java-node:11-alpine@sha256:e2acac347631d42ae5b5985bd801e8c48e0429b4a85f6e435c57cd5321a773a6
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
