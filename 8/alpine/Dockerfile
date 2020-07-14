FROM timbru31/java-node:8-alpine@sha256:6221ede4baeee3c11724fcf62121f4e1d585b1e8999b71437a7c85b75253dc7a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
