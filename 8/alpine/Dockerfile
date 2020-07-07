FROM timbru31/java-node:8-alpine@sha256:1e158aa6df6df25e6ed8ea50f28c4fa36513235e0bff11ccd1ccd8f6012a8b74
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
