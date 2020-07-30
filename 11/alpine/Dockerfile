FROM timbru31/java-node:11-alpine@sha256:1b5fcb8a5d51311003e9e318be2e1c89a241edfc88e6dd4ea166e41768af97ca
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
