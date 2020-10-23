FROM timbru31/java-node:8-alpine@sha256:1f3f8aa3fcebd966ffb0d23ae1c0b6609f45e770a4cb918d593609768c1d7219
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
