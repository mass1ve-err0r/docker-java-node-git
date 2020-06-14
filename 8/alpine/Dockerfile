FROM timbru31/java-node:8-alpine@sha256:7ddc8347d9e3c16cfa112d5e2de9681f724d2aa80b8eb191c16d998f87f3d10d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
