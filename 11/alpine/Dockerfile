FROM timbru31/java-node:11-alpine@sha256:a14c624684f683901d9dede85a95916f66dfa816b06c0c01339fa527aa1664af
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
