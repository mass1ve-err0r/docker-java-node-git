FROM timbru31/java-node:11-alpine@sha256:853573a00f17c10cda6503b4af0aedf62eee0cdfcbd06b4bfd77813ea1429528
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
