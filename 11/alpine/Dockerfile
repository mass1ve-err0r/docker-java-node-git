FROM timbru31/java-node:11-alpine@sha256:0120ef1fc7fb023b7ab5eeb16b9ac3efde4b4aa047b674ed9790a45bbe9d3dc5
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
