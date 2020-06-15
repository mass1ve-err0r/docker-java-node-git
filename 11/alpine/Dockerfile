FROM timbru31/java-node:11-alpine@sha256:6d9af63475ec3e677d98825210d1ff38f27c8d9f209203b45fc8959dd5a249b6
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
