FROM timbru31/java-node:11-alpine@sha256:0dfe1d3f46fada617c022d74fc44ed02a2ad508117da99c9ec2323fe01e3cc1c
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
