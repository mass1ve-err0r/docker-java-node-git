FROM timbru31/java-node:11-alpine@sha256:0137b658c7f79fcf20357c1cc1954ac7a18d413497755970ba5de246523bde3a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
