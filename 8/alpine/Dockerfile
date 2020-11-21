FROM timbru31/java-node:8-alpine@sha256:334b8f97d7ce8bf856bae934c6551237d1150d85d763d1b3b502dc7c0e3f3da4
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
