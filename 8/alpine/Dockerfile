FROM timbru31/java-node:8-alpine@sha256:887e70a7fa007432f2806e9a8ed8e05c3a1c36ee24fa70179464609b81f93c2c
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
