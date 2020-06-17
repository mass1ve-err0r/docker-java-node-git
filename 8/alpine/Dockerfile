FROM timbru31/java-node:8-alpine@sha256:614cc6810fef813a8a82aa6bdc2e8acb5d4280a14f7dcad86a98a80fcd090dbd
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
