FROM timbru31/java-node:11-alpine@sha256:cbe3c8d63e628aa6116c5acd58ab35fd16f3e26e7fdf9475ecbf68bce9cec82b
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
