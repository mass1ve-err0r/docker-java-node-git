FROM timbru31/java-node:11-alpine@sha256:e69a68b0a621a19c65ea04807fb1faefabdc210ff892a9e3e5d86d318ca9beac
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
