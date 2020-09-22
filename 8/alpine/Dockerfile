FROM timbru31/java-node:8-alpine@sha256:96e8eb125b27318d4eccbf4c99d1c0df3ee73129f3025fe78f8a847eca38e870
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
