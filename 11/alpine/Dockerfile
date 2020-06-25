FROM timbru31/java-node:11-alpine@sha256:44be7fcd2e20ee4fbb36f1ddcc59362b3c1d678a95128cf0549cf6bbdcdc9188
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
