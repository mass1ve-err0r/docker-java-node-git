FROM timbru31/java-node:11-alpine@sha256:77c5119a6065abd0f09fdbe213a6fc1e3910940d03c3375dabec9017cee5583c
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
