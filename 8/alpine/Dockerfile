FROM timbru31/java-node:8-alpine@sha256:7425f8745b72ea29df1716b3730805f11791281a2506fcc0b6523406988050d1
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
