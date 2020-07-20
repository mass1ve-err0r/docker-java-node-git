FROM timbru31/java-node:11-alpine@sha256:435ae4cfdffe5cb45aa5a47c7ce1f4e948cae7e8aba717370fe09ee692d33f70
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
