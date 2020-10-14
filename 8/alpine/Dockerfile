FROM timbru31/java-node:8-alpine@sha256:aa5a465acebf670c88c12f6df0096ad6cf1277462bf6b9d9bc94e52b641e59ee
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
