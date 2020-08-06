FROM timbru31/java-node:8-alpine@sha256:18c5aee99a5a1b87314de053fbbe2590ffb3e7b1c48eba7b310506c8d0088f2d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
