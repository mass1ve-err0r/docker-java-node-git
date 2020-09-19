FROM timbru31/java-node:11-alpine@sha256:977f68dd5caaeebbc0bef494fcf9d1bbd155517b6d3bb85977d4fadb2e59606c
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
