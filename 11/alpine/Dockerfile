FROM timbru31/java-node:11-alpine@sha256:b1bfd54361c7ab63523f02197f5b130c0144bb5a5e2256893dcd2d83eefc071b
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
