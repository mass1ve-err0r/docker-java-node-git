FROM timbru31/java-node:11-alpine@sha256:b71cc9a5026aed33b2f5f5518935bd322662b6163942301160aa53dd11bbdc04
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
