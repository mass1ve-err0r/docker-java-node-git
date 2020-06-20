FROM timbru31/java-node:8-alpine@sha256:ce5aff29497b9bece6bf47f9e4550e71d5d0ad05ce47c4a128302849348e3afa
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
