FROM timbru31/java-node:11-alpine@sha256:a7915ae838eaffa2cb27ee6d6fda20690cb42312e251aa9d4aa454f779f2fd9a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
