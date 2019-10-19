FROM timbru31/java-node:11-alpine@sha256:bc118bc1f900742c01b6326fcf410de8311d7e16e16086d7b1f7f890e4321ee1
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
