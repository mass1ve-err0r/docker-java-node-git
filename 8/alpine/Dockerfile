FROM timbru31/java-node:8-alpine@sha256:eda6aca0de3b758b95a58597152b1109e56c848425a10943d5769985c3104c61
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
