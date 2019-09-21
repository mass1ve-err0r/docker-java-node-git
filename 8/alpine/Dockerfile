FROM timbru31/java-node:8-alpine@sha256:fc3a52d9083657255636489a00bbddf72c6c9789cb01a4c65c8086d7e4db53a1
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
