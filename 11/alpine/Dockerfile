FROM timbru31/java-node:11-alpine@sha256:29b4054a47e054a21003a8d7b55eac7c1b4a157df78f1aa22cfacd767824e497
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
