FROM timbru31/java-node:11-alpine@sha256:a25eed5448254c1064c1f790589cb0a9890a455df157147d1f5d8ca474644d97
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
