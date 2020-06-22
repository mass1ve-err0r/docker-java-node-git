FROM timbru31/java-node:11-alpine@sha256:4f3551940df94e9063bf60f7986c2c0ddb8833d696ad03ab23ed08b1fa5f5445
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
