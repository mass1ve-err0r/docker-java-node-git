FROM timbru31/java-node:11-alpine@sha256:46688a4122649c9e0d0a315a469b450a35563bc8258e2eddac7ba84f99e6fe7a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
