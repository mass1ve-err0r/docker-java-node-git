FROM timbru31/java-node:8-alpine@sha256:b39c1f66def22ccf624c380210f2dd670bcfd40d9499327d02a127abe38151b0
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
