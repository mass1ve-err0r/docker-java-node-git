FROM timbru31/java-node:11-alpine@sha256:f65209ae8f90e62e29e5dd3878e2e8071b46c12f0067ed1bc55362029afa8342
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
