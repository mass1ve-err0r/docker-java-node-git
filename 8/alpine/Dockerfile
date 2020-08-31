FROM timbru31/java-node:8-alpine@sha256:1310033e3bb94a09f7fa6cf33044f98ee175bd258dd010bb3b8ea844552fe4a1
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
