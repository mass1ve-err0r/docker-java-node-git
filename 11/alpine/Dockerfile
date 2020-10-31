FROM timbru31/java-node:11-alpine@sha256:6a78004eaad99f2074bbb94abc1f8b6679bc097765b5bf78f59702863eb033e4
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
