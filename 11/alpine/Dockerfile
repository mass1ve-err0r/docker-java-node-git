FROM timbru31/java-node:11-alpine@sha256:849697690947660dd1cf52b750b87521c4de35cf7261e140934ebc1d46f10892
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
