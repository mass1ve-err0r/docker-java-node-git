FROM timbru31/java-node:11-alpine@sha256:205bd7e2ab1e766050be3eec4f8a4ef660f698a6a1ff49d227b6048af94bff8a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
