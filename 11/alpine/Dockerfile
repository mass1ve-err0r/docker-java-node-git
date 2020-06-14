FROM timbru31/java-node:11-alpine@sha256:a694cad6a63f303a566909a0d08079796aeb910701e49a93970a699f64cdf493
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
