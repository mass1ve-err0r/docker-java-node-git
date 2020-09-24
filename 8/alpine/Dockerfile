FROM timbru31/java-node:8-alpine@sha256:fa776a32102b64b589228b3b3ea3b2fa14ece4447a55c62979823aac85ce26f8
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
