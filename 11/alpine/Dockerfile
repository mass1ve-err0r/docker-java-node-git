FROM timbru31/java-node:11-alpine@sha256:f6a8fd116b3ec951a1e7a5c5a0b0f1861d5e49f8ed622e361fec5001cd23957c
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
