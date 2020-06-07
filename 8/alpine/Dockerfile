FROM timbru31/java-node:8-alpine@sha256:47bf4306b13c524cd4872ab63db6068c04bde8419dd2b1d3a03bb8592c16d8b2
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
