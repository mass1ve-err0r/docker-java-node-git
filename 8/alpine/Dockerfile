FROM timbru31/java-node:8-alpine@sha256:9732e5d3d09a8396ffc9c226bee1a912630b230d76300900a7b2100142f0c05f
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
