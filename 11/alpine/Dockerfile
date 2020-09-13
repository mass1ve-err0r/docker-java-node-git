FROM timbru31/java-node:11-alpine@sha256:434b7878143c909d50629104b21308fe1e9e4708da4147a1a812ed455b61479e
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
