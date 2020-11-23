FROM timbru31/java-node:11-alpine@sha256:04cac26bdaeedd33f95677051a107769bbebeefad99b275834b76ac9f8ca6b8e
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
