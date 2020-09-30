FROM timbru31/java-node:11-alpine@sha256:6bd7d076fad01e405a0c25011981f49c98c4a88454b731edf5c223702c083c7c
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
