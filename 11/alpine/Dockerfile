FROM timbru31/java-node:11-alpine@sha256:05584ef871703ed52d588de26870a8d400f53e9e093a26008c9f85bd34243bea
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
