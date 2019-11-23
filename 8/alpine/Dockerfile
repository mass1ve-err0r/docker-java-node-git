FROM timbru31/java-node:8-alpine@sha256:8f2bc90d9423a2d030013396ac3e8d7a485d78108508725c317d7736122bb3f7
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
