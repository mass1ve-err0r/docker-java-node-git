FROM timbru31/java-node:8-alpine@sha256:61fb2538ce30738fbfad079a52c8c1d55bf41cbe49f26ac9b6a4525b5e4a5b5e
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
