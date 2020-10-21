FROM timbru31/java-node:11-alpine@sha256:105c57f386dc6029fa1eaa0573685c848be6505db76fb4b0412ca802ef825f82
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
