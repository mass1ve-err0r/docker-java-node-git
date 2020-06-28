FROM timbru31/java-node:11-alpine@sha256:172fbf6cc6200f20379a04353d5ede6e8132f93d172e75ee4ebad655fea64a86
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
