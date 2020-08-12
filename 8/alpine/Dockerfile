FROM timbru31/java-node:8-alpine@sha256:9a57b50a7ac9f30120ebd87a7817efcbcfd1b52203c310d9a289bfc2b50d3dc3
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
