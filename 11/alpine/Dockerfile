FROM timbru31/java-node:11-alpine@sha256:1600f3a0e73da472afe4011860a1c42909c46b2ee0c4c17349b59013005725fe
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
