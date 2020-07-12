FROM timbru31/java-node:8-alpine@sha256:196afbf312a76c5545da1c0531cf00d01f6b8e1ddce03c10c64b8671499bf8d0
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
