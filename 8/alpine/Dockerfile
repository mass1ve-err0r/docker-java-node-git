FROM timbru31/java-node:8-alpine@sha256:f18e0ac10f1d877dbbff03f36fe5963cef768caec02f362579f3407d8057107b
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
