FROM timbru31/java-node:8-alpine@sha256:23d234e142f43fe74bd20193812d6de156451d226f8f375e29a0f92127265910
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
