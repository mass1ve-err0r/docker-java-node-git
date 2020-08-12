FROM timbru31/java-node:11-alpine@sha256:ac7a4c2129fc69937ec43034c3df3325afcf1b0864082c956415340514deca21
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
