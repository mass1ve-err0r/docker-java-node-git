FROM timbru31/java-node:11-alpine@sha256:11385d898cafd04ccec9cc0fbc95139a8b7802358529adf2aba07ab535e3b9a7
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
