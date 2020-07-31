FROM timbru31/java-node:8-alpine@sha256:e35bebb2ddd2a87e0aec12db43ec88cec95d6186b923ae46612a304e2d02c92f
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
