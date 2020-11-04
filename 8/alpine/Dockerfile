FROM timbru31/java-node:8-alpine@sha256:e5e0366c9bc00df1bc66fd0ba300c6b255995bc06963f09e5bc29d80796600b4
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
