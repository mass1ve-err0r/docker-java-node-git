FROM timbru31/java-node:8-alpine@sha256:06abde07c675dbe5cf507ff501c3c95da8bb017471faa9663485f9f9f722d905
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
