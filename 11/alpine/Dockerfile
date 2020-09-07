FROM timbru31/java-node:11-alpine@sha256:edb85dc074299c7d2bb66bf2d96a0fd44145e76024f0eae30643bdaa27452128
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
