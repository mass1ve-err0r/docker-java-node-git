FROM timbru31/java-node:8-alpine@sha256:d42bc7685f1085452471f2c6c177ff7927394f965d4cbb45eb1c49d45af8dc1a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
