FROM timbru31/java-node:8-alpine@sha256:4aa3de83a2af2b3b1c07e0f1ff44ffee20cb5fe26ff300a5e17c591035839fbc
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
