FROM timbru31/java-node:11-alpine@sha256:f673ca86f640636af22e032c2310354edd22870e3673e6b949021e67809e7440
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
