FROM timbru31/java-node:8-alpine@sha256:23b5f529f7b919b48452af5918c8f229c44ef798497bcea21e1400be0cc475f5
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
