FROM timbru31/java-node:8-alpine@sha256:c66e0d29ef2704fe5f4ff5086807db597bd581515e893d418667f0b7e8adc7b8
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
