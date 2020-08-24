FROM timbru31/java-node:8-alpine@sha256:315922b86a72b6d5d6c39787b04192e8a34bcccb3e59d142c9a8f2fd501d302a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
