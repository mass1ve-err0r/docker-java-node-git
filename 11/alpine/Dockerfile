FROM timbru31/java-node:11-alpine@sha256:2b82b64aeca233589f603872c5f7a46ca7de69f0b01b9727005c9c6e6df81889
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
