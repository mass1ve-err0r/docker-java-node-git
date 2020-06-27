FROM timbru31/java-node:11-alpine@sha256:02f87f9a3fbc94a50c06878e2915dc1efa9c9f97f892f6addc5f903107c878d7
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
