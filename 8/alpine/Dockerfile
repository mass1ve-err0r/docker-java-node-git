FROM timbru31/java-node:8-alpine@sha256:94a5884bd88c3577d4d8d1904dca1c3d00f15793d3290a338183f623a0fbbf5d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
