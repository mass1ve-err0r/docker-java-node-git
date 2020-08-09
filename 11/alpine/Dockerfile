FROM timbru31/java-node:11-alpine@sha256:187b0add3382e34045600b4659cf6945ff4b2443ad82093505374794a14e16ad
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
