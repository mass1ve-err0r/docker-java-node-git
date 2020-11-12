FROM timbru31/java-node:8-alpine@sha256:5e11a0a48b95a4fc422d031e4f2669e482af6aa6389380f432026e32077766f0
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
