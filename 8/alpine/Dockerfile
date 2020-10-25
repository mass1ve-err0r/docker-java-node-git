FROM timbru31/java-node:8-alpine@sha256:0b472c12648e4c594350285fda14470eb1c91e032f29942e249ab035ab187dab
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
