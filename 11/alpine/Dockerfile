FROM timbru31/java-node:11-alpine@sha256:c04dc7002b48c381c131ee7d490dadb352780a051b82218719eb88017cbe84e0
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
