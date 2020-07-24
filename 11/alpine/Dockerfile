FROM timbru31/java-node:11-alpine@sha256:e11b569037a900ce2ab0e3f0469f0621c076456fa16505e40b4e17e524682a58
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
