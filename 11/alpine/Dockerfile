FROM timbru31/java-node:11-alpine@sha256:aed6cded82c98030b502c3b6357eb4ce594c7496c418591f5a4f48a6a8174ad3
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
