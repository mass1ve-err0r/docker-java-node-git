FROM timbru31/java-node:11-alpine@sha256:80064b8473b10edbf83c4a70621050f63221c2132978b27f11e77700fd7a8c6f
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
