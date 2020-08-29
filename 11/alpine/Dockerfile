FROM timbru31/java-node:11-alpine@sha256:af799355fdb381f1af0c4127fb2a6d2ced6ef422db55d717f7b4eaf2f4e47bce
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
