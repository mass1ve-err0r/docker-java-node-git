FROM timbru31/java-node:11-alpine@sha256:e1c7dbd524a11b0d0103e6e04284101e8a2dff495d2bafb406d7a5efae3541b7
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
