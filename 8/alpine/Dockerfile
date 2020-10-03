FROM timbru31/java-node:8-alpine@sha256:56461ef7c2c7ac9c982b7bc5e67d6d4ebcd18e8b764780c16a511c00c884e1f6
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
