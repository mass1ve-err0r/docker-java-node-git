FROM timbru31/java-node:11-alpine@sha256:e3a082911a44d761251a886d4fec48796b19f559eda90cea935fa8913b111934
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
