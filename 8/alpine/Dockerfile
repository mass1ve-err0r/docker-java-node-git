FROM timbru31/java-node:8-alpine@sha256:ffc65673b8322d4d27ecb56dc51008998d5c69d0ce1d9b20c8b761ea3b067d54
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
