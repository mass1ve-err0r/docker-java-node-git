FROM timbru31/java-node:8-alpine@sha256:e15c43b27e772d69c2e32e1e382ba4728efdaa3e392f988a2fc9ecec9f169aa4
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
