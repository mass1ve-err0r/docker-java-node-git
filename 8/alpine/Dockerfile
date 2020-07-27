FROM timbru31/java-node:8-alpine@sha256:7eb72b042f4057176fd47d3deb76d30568a3e15be50548e2c5b1e3dea00b2b84
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
