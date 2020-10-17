FROM timbru31/java-node:8-alpine@sha256:c43691d05207e959a5439c8b8dee2494abf3078f6d019b68f25cca2ad1560080
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
