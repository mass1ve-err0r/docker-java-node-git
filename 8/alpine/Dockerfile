FROM timbru31/java-node:8-alpine@sha256:8cfba30dcf3f115024a0f577965859916542d197a8e4845f1f57dfbe0ddf290d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
