FROM timbru31/java-node:11-alpine@sha256:7460638a0bbcb3b6cdf73dfebb2e0a2d2b3f8cacb33d42d96a79d7e57fb869f9
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
