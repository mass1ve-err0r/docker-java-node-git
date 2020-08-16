FROM timbru31/java-node:8-alpine@sha256:84fa4dcdac9cb2d17a690205296422dcb6c1e32ddf2fd62b6150483a33882806
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
