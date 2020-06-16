FROM timbru31/java-node:8-alpine@sha256:8613f52bb2769feb68ebc15bbb5c9fb25a2a9614c4aaa45a9d58b978cde33cad
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
