FROM timbru31/java-node:8-alpine@sha256:6af444d3d3a1332ad45f125245d84a78c5047e8832ade52e3ff16c18cb466fa5
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
