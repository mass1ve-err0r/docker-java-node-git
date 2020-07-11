FROM timbru31/java-node:11-alpine@sha256:caeefa062f467f210c7041d3944f53deb07efa72c65114bec6e4b04fb00b94d2
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
