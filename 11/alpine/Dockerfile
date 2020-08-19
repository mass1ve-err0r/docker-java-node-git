FROM timbru31/java-node:11-alpine@sha256:588279c579f0635b00d1863ab2c0b58d39e67465a4555728a8e19e5f3ff6a0d9
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
