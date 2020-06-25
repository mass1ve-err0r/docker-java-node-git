FROM timbru31/java-node:8-alpine@sha256:2742cc1314d8fda346cd3c4de68a0d355e0fe6097c10611f2dbfec3de1f88249
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
