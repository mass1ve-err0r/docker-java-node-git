FROM timbru31/java-node:8-alpine@sha256:4c03cae956f52ddf084fafee41b126e280cc4b37d99cf6cc739ec7ba1f0d2963
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
