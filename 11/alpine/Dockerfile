FROM timbru31/java-node:11-alpine@sha256:621ca313fb9b81a818759df990e69c8f56b8c96952c73c2822e96fcaa2b40761
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
