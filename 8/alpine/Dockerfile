FROM timbru31/java-node:8-alpine@sha256:5a884b73309e9859d0321cfc6f1f74256e23cedf2b0a3bc1a225524b08411a3f
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
