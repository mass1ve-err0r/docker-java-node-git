FROM timbru31/java-node:11-alpine@sha256:1c59bbf644bf5ed11b741af5c7b03267082b5e2607b2476db82635f11daa1c93
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
