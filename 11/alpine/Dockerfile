FROM timbru31/java-node:11-alpine@sha256:1152f883afe95059e6fb78b77b13a8566914e1bf29b2108b166325c04d166c34
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
