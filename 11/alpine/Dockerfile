FROM timbru31/java-node:11-alpine@sha256:2d439aaf8ad203685adae4498a83ffe78afb8c83289706c17e1e09523b00193a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
