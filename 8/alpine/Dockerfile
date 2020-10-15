FROM timbru31/java-node:8-alpine@sha256:3def404289f21f4362fb1f235a933036a6798588eeea1e4689317280575cdc34
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
