FROM timbru31/java-node:11-alpine@sha256:7ed3e93c7edb32ff67e0ca57fcfbac7d8816e52a01846d3f6f1f065a6c9d509d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
