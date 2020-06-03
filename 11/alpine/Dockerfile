FROM timbru31/java-node:11-alpine@sha256:c8f4674b996118583abf3010d3350f762dd305b01ef5c1f8fc3d087f35f5d8da
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
