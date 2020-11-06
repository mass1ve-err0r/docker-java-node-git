FROM timbru31/java-node:11-alpine@sha256:286e41a13e90e038d709ee988374e56ac0eff75023ef6ecaa842546cc0ce9a0d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
