FROM timbru31/java-node:11-alpine@sha256:87ca348b037af29f3f9a5868dc67e74988c8a08e2d8369745c19fcb68ba6ee1d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
