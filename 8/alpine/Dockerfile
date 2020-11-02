FROM timbru31/java-node:8-alpine@sha256:abb89fe98e20f8aa3667c8d2e0e78025cc0b845fa80763cb0c9f1ea1ebbc4826
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
