FROM timbru31/java-node:11-alpine@sha256:867daf5638163ff5924814ff4655047c7e668f1aab724d3db17a7904ed95d2d7
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
