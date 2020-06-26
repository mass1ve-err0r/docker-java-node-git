FROM timbru31/java-node:11-alpine@sha256:999e65add5eba6c35a6a7a7f9f3cfd99ac68f493c5eaaba6d74ebc2e8ee51f0d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
