FROM timbru31/java-node:11-alpine@sha256:701ac123eb75ad787da3efe081b0de1825baa6a122071081e9956790ab96cf9c
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
