FROM timbru31/java-node:8-alpine@sha256:e5ff1cea0786ed08fac44f2e1211efd9d58233854aba37d6a3cf8a92012e15bb
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
