FROM timbru31/java-node:11-alpine@sha256:58ae6cc23a77993c82d5e6534aa0bf504f35a021c408c60a4ad3113831cc61e1
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
