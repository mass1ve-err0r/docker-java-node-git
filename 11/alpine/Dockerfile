FROM timbru31/java-node:11-alpine@sha256:62e9fb132df09fccfcd8e68102944427fd9eff48e8ef91f076703bd80198d69c
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
