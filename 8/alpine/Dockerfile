FROM timbru31/java-node:8-alpine@sha256:6c817d9430b00a59bb371a0d4055c454a9fde1adb15cc2c21da54c0fe521770c
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
