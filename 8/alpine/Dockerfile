FROM timbru31/java-node:8-alpine@sha256:1ed84ff74d16faaeab7802de7a17779dc7fe55e11d4bd7f7cc9c61babd2e4b65
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
