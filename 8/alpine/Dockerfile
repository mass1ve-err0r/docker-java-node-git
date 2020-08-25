FROM timbru31/java-node:8-alpine@sha256:05be0ca0149c760cb1f587cc9a96c7f5942a891b0e3bc67338180a7f7759df15
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
