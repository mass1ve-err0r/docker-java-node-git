FROM timbru31/java-node:11-alpine@sha256:9c7def8839f5b700e080eb4987c986913d0f4be3395bc8eafbfd8222fb5ad6d3
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
