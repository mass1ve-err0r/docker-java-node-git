FROM timbru31/java-node:11-alpine@sha256:d74fa06e8f6e18f95ee55b4e3742b538c7377fd71c2e0fff4196a7555e24d92d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
