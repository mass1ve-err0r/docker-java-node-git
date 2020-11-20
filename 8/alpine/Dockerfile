FROM timbru31/java-node:8-alpine@sha256:f63b129716e4aa5c8901169f1773b3e169f51ae65f5d8064d60fe9c4921bd8fe
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
