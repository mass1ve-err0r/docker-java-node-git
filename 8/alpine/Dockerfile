FROM timbru31/java-node:8-alpine@sha256:f1e9827ddbcd707a72c9b4b51993aad9c1d323ee4498ffff3933e3bd3c450f5e
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
