FROM timbru31/java-node:8-alpine@sha256:a66372a200b83b9d4377d37fd632cac959ce17b604f50c2a0d9fd8dd8300f4c7
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
