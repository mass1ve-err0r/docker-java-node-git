FROM timbru31/java-node:11-alpine@sha256:dab85728434174a6f1cdba5957004d1c5fdf7106d3477b0dc212989dcae83fbd
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
