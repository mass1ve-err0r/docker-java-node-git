FROM timbru31/java-node:8-alpine@sha256:4645bf39a5c07cd80cad1668119962fc31a60a0f3104fc2dab3f0dfcf409dff7
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
