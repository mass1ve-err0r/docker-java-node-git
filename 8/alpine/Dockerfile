FROM timbru31/java-node:8-alpine@sha256:0570026a426ac8634b1f729951618b747d8c8bfceaa1aa0918e4890c473acdf0
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
