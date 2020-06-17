FROM timbru31/java-node:11-alpine@sha256:ba26b23dde0999510f009985f79805f83608b167d2dbfd3e3778865aa56e12a7
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
