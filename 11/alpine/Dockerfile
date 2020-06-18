FROM timbru31/java-node:11-alpine@sha256:ac6246130a8e56af4f8ad48a41e7a694f8defbae45502f3fef8abc4d827bd6bd
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
