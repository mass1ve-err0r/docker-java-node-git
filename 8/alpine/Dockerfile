FROM timbru31/java-node:8-alpine@sha256:856557444b3553060d00f89989abc4b7bb0d41b372ef1523f7b018e08292d822
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
