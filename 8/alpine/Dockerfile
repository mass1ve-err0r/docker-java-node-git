FROM timbru31/java-node:8-alpine@sha256:da7f869e59c1620c828af8d559a934db587f39e6a4220d362cf4d06eeeb05eb2
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
