FROM timbru31/java-node:8-alpine@sha256:5c6cf671230430f437f172570bbfcebe185fe91f37b659318c1ae121c735b441
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
