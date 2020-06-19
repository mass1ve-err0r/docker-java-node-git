FROM timbru31/java-node:8-alpine@sha256:16162deefc8cc75e268f4eee7eb64be52183af01842e9afcbad877f984cd378a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
