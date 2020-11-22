FROM timbru31/java-node:8-alpine@sha256:405c7de58f02765b0fd5957b90c6b8cd6086781a1de328717d10186b31f00870
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
