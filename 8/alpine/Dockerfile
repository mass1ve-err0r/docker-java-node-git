FROM timbru31/java-node:8-alpine@sha256:9abf2dceedf9ba70225074c2fda69a33d8e9e8190fc3e3a373f88b95aa6fee47
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
