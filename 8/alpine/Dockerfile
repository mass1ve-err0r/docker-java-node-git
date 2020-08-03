FROM timbru31/java-node:8-alpine@sha256:df56bfaf024402206e5d25c937dd9e19817305e0ae336836300830cff23f7b63
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
