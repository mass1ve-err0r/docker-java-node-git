FROM timbru31/java-node:11-alpine@sha256:48bb525176a97ed77e5132e5940cf66f05e3c852ef53510fc0395f5ff9ae259f
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
