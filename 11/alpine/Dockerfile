FROM timbru31/java-node:11-alpine@sha256:0dca3b654d4f11cdd83a26da8609f31a7e576efec79e25bffd09199faa5d0d06
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
