FROM timbru31/java-node:11-alpine@sha256:9659652a04af0a6603a6c65b746d9cb8b99d78ba4a1bf34d172f8877330fee3f
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
