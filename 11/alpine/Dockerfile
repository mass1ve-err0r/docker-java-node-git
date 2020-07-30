FROM timbru31/java-node:11-alpine@sha256:5805b37a4f9dc573b14417dcf5201464791ba365999f84aae70996369aeabcd4
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
