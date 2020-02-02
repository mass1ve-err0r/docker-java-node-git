FROM timbru31/java-node:11-alpine@sha256:c0c13894ca3241b05b32bacea971964f0123d180aef48405bc7df39fbe097108
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
