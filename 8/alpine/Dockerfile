FROM timbru31/java-node:8-alpine@sha256:9c928832c6ac86576b6d3ff3c73de1818db0abe57c2bc154f5da9dda64b9f4a3
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
