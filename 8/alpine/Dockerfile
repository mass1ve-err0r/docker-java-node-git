FROM timbru31/java-node:8-alpine@sha256:fed38092764a53e59234368381636a9037ab36edc9b38b8b4504261b993d721a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
