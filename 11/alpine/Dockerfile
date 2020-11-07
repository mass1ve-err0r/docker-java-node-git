FROM timbru31/java-node:11-alpine@sha256:434713b5c438b51b0d33dc9873fb90325d5c8d0db969bf8aea0ce2af79fcb50d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
