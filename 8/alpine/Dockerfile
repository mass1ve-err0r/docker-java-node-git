FROM timbru31/java-node:8-alpine@sha256:0918ac01cb2fa4c06d72a2c645acb1a58d66d07aab79e7cc729ad984b5cf574e
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
