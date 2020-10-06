FROM timbru31/java-node:11-alpine@sha256:f197a7aca0f027b4b5b17673e590e823739db23f1e6738157e7879bb4ed62fa2
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
