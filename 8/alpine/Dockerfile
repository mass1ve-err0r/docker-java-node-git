FROM timbru31/java-node:8-alpine@sha256:1ef23612879e2bf539a9b4bae088f3a967fa216201a2bb00d5209dc7aa42989d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
