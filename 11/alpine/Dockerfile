FROM timbru31/java-node:11-alpine@sha256:7f9468073ecd38e8067df31ef1982cb5018ae42f1706d60f14ca6e5007cff157
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
