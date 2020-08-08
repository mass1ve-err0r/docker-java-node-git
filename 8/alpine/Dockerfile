FROM timbru31/java-node:8-alpine@sha256:b577df87db48f48b9e1e6053cf05856146e884ebd914f012f9f047342db9e62d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
