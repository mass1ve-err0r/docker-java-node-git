FROM timbru31/java-node:8-alpine@sha256:d80fce639bfe4769f7290654fd7876aea01c73f5f53f35395fe87fd07ddec9fb
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
