FROM timbru31/java-node:8-alpine@sha256:8efdeeb99b7c8ecd875b207e41d05e5d26deba124c6eda9e708d9c53c764f354
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
