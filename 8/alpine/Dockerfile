FROM timbru31/java-node:8-alpine@sha256:8a682d6a2026a4afa1f82cd830be5bcc4a0fc7ce8c1d1d137a02dab6b9344735
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
