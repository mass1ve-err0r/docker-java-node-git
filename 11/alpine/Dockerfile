FROM timbru31/java-node:11-alpine@sha256:74f78a3e3ddfa9112cbb05f798d293c030b8e8299a2a8fea3ff0042a17420c63
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
