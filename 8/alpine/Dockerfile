FROM timbru31/java-node:8-alpine@sha256:214861106ccdda555550f7d48904efaf41be3e4e8a8a4fb7e2ba56bc9f69c418
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
