FROM timbru31/java-node:11-alpine@sha256:4061fa292a72c7fe50783b1a5d9092fb3649d4a091ad5c394c60a58a8a67303d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
