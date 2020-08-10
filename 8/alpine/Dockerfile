FROM timbru31/java-node:8-alpine@sha256:a56e7c55c2506e4cbebef8780600a97a4d0c6c64e99a8409581d889fb37e35b9
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
