FROM timbru31/java-node:11-alpine@sha256:83f37fd4d49f8926438576f07edd5ad87aaeeb3ae9eb7d17df5a7ed23aace340
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
