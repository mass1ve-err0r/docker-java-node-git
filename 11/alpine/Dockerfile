FROM timbru31/java-node:11-alpine@sha256:404db4aa5bb28dea6e5cf3ab37650ffe9f661fd5172f47f71c328e7ada1a65f1
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
