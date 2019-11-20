FROM timbru31/java-node:8-alpine@sha256:6982e2a6249beea948a6981fa59bb45e6f07aae18c5ad219ac45d0a4844deb8e
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
