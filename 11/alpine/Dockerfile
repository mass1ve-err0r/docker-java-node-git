FROM timbru31/java-node:11-alpine@sha256:d554b13e9dde32d1dff3b39640522da30aaf57a122346065b72fdb3d8d85b809
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
