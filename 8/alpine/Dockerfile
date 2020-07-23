FROM timbru31/java-node:8-alpine@sha256:3ec3d07832ccd562fb16cf8fa40f8337d1f8025795e965c8f86cb8f55279658c
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
