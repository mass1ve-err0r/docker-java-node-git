FROM timbru31/java-node:11-alpine@sha256:56b65014826e7ed39102091bcec4a5e11dedb6abf9c6fc5848896b39a050fa2b
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
