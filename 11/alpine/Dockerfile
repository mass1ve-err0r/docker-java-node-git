FROM timbru31/java-node:11-alpine@sha256:d1a8bd765d3564ecb4ffba8f06ef74f113b97d5a41ff4ecf3294a84a37a6348f
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
