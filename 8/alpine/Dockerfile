FROM timbru31/java-node:8-alpine@sha256:c377bcd3d2e10997539d4ee6fed8f7713cbff40fb9b5b71245edf427c4772031
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
