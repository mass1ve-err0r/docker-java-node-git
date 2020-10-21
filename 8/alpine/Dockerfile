FROM timbru31/java-node:8-alpine@sha256:bfcbacccd8d98b415f24783a95a1e3d992a25ced51d31e8ee132534d768d83b8
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
