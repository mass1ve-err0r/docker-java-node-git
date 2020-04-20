FROM timbru31/java-node:11-alpine@sha256:f197d6c5bfd8ee77f1728d42d491ec097599a1c7f695935f632f934c4e9a5fbc
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
