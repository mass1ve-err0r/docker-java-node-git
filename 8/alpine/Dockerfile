FROM timbru31/java-node:8-alpine@sha256:d19d577031cee6bc8345321bfc19831d8df0119de8c24b34658cb25b2b3b5266
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
