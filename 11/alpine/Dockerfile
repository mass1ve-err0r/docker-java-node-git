FROM timbru31/java-node:11-alpine@sha256:2d1f2d5fb3015d7722394da5143f8254e2f858ded18402581aee6a9f7119807e
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
