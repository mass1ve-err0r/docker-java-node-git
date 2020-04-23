FROM timbru31/java-node:11-alpine@sha256:5dcfc39c0a2494b3ac7100c5533128a0399e4a557080c79e1c36cc9a284f371c
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
