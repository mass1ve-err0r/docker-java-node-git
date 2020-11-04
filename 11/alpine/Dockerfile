FROM timbru31/java-node:11-alpine@sha256:574ca49fb17517981d9a255a86819e169dc24292222742c1722703ceb5d8a870
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
