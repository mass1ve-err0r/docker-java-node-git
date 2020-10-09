FROM timbru31/java-node:8-alpine@sha256:212ea27b6fea944a149550ad9a3a6e32d4688b13c0faab49301c576241c35c5a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
