FROM timbru31/java-node:11-alpine@sha256:fba185f751304cc644d1c9141dbea1ee577fa75b9c0e60a6b45641012e111920
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
