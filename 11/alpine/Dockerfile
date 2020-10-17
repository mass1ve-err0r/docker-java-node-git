FROM timbru31/java-node:11-alpine@sha256:db84dce862c1ca16b3f2af955b97daf6ade75b7090f0213ff1a65bcdeb8e0ab8
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
