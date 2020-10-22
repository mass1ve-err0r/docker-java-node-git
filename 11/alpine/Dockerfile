FROM timbru31/java-node:11-alpine@sha256:e87626309d0a1cb2a48a91b7cf3271a725e2b4e4a7c726696f30caefe453ae6c
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
