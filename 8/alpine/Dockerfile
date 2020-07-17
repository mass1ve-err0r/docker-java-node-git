FROM timbru31/java-node:8-alpine@sha256:efac793d389e6acf7b579fdb3fc8c6377c8d6649359115b4f408efb612d95812
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
