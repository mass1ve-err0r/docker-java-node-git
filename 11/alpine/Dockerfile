FROM timbru31/java-node:11-alpine@sha256:6ba8cc473d0d621080ccc07705c3fff2eb0fa872127d6a33bd5b7e3f1a9ac8aa
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
