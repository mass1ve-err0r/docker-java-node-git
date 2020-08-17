FROM timbru31/java-node:11-alpine@sha256:37620c5f594018c4cbe0fe3cbed850ea7046305a8467eddc33d24329f69d8177
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
