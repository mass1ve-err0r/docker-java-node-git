FROM timbru31/java-node:8-alpine@sha256:bd7f0e91d785537087279593f72cf339adfab0b0c1b913f823783677ffa4cd45
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
