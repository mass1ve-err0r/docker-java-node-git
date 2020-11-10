FROM timbru31/java-node:11-alpine@sha256:aa21983777970ce986a15d35e2a01c4ad5249750e5d6db112aff7bd4f1359e0a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
