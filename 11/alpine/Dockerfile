FROM timbru31/java-node:11-alpine@sha256:6524b5b23bc623751b66eb57faefe0e34d19f9d75710e4f70b8ba15a4f4a54e3
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
