FROM timbru31/java-node:11-alpine@sha256:9ca38e0140e5c0b8f873c62dea6e2d02088ec4cc36f7b3b05d01477ceab56a4a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
