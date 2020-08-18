FROM timbru31/java-node:8-alpine@sha256:80292d16a95f24b704900a6ea20a0c23ded35007c6d3858dc00c6806ddd72ce9
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
