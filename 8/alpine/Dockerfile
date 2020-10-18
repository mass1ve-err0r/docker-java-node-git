FROM timbru31/java-node:8-alpine@sha256:22a4ee13afbd4858a82271f95fb844d445ddfd8660d3457307d4f08b56f3931e
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
