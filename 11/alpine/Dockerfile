FROM timbru31/java-node:11-alpine@sha256:d5f35726c68812d71173c5a238e9d6f0f92f8a4a7af755e4254e39f011a4dc5b
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
