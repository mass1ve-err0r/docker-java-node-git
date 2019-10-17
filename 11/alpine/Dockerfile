FROM timbru31/java-node:11-alpine@sha256:cd7a52089d2013887563ce14b24f6f97c45c77476e0b2ea465a9583dc8dce8b2
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
