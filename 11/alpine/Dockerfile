FROM timbru31/java-node:11-alpine@sha256:6d391f0014ef89f064b1b08c80e0c09d7b2ade1176af9731f2ae77677e5cee40
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
