FROM timbru31/java-node:8-alpine@sha256:f4356a8a507d821f6acf0f8ccd849de4c0a6c9e91f5670bd26f85ee57f1f13f5
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
