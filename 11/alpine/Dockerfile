FROM timbru31/java-node:11-alpine@sha256:3cda67729a010cd126c741d5d62f1492a2d6c4231024ba385c005b2fc7995aa3
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
