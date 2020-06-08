FROM timbru31/java-node:8-alpine@sha256:8c72ef05ac10148c596f655d7eb90b5700cb7d8f4306a8e730c9fa8387095aa0
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
