FROM timbru31/java-node:11-alpine@sha256:f0666fa25cbd32bb7ebfc010171f067e01fd6aa33d17a390908a30091ddf1f71
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
