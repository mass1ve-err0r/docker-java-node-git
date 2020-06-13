FROM timbru31/java-node:8-alpine@sha256:024d0e6eb3035602036184c2415681c4ca906732daefca4f67dd6e9cdeb89779
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
