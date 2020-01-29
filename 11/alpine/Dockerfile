FROM timbru31/java-node:11-alpine@sha256:cf0897a3df3e505fa580fd8f936139d2626abf0ff7bf5faa29dd040cf991094c
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
