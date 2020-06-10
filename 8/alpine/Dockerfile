FROM timbru31/java-node:8-alpine@sha256:54132af6ab811d1ba247f9490a95832792d9bb19a5c228f25910a419f2753da2
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
