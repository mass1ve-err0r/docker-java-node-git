FROM timbru31/java-node:11-alpine@sha256:6d9643e3682acd871e028032e58e5350def40fa4a0ab4ad71643efeb0b604e86
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
