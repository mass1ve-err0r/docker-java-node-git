FROM timbru31/java-node:11-alpine@sha256:7febc8e1e943c2c37ddcd66466e2a7f2c3d5dc8f1638385dd90eb8d73801ba65
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
