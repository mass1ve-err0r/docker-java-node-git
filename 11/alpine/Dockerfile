FROM timbru31/java-node:11-alpine@sha256:626d4a06b3797f481ddf01bb22a43cde31ac9333cb54cc31dab2e95f5b0ee068
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
