FROM timbru31/java-node:11-alpine@sha256:d91904614c75dde5ef233f0a6669081fdb48308890d8428668b735428f9a32f9
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
