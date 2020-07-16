FROM timbru31/java-node:11-alpine@sha256:c8c1d60b1367b33a6fc7c80d8e8e395bcde604e2b4a7f2937a974e78f953ce6c
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
