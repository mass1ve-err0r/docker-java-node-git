FROM timbru31/java-node:11-alpine@sha256:6ef4c9e18165be76531d1d97ab0f99988a0fc206b01b388c9a40cd3853d12369
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
