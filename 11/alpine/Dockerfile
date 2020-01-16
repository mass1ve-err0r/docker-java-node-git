FROM timbru31/java-node:11-alpine@sha256:3698281936ab230338e2bb32775868dc3c8a921b78e3a94ea94f41ce29bfbac6
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
