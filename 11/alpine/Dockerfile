FROM timbru31/java-node:11-alpine@sha256:9514e0b9b22a6f8ff97daecb56b591fac3930e25df90c510a9622bf2c6b92dd4
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
