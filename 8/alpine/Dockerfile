FROM timbru31/java-node:8-alpine@sha256:9c57159f24368189956d532a530f1e0b78408dbada5d60b1d655999d02df8f09
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
