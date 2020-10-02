FROM timbru31/java-node:8-alpine@sha256:b154a2ed2be43808abf8aaf7ea8737af53e55d34ff875ec945cbfe7e7f23d747
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
