FROM timbru31/java-node:11-alpine@sha256:0b3abfc7dd908be2d217bf802bc28da1b50f17c89f6956fc56cce1fdda5abe6d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
