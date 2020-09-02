FROM timbru31/java-node:8-alpine@sha256:cf5e793687a2b774e8139b73fc0f4886a4870c098ef5a17f311319e4913a47bf
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
