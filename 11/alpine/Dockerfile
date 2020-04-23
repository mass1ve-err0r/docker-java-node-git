FROM timbru31/java-node:11-alpine@sha256:e22dc2c835d3a1ef8392412f4df148d0b6d2d93eb0604008e7c9da1d1c1eb933
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
