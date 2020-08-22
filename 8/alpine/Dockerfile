FROM timbru31/java-node:8-alpine@sha256:164197084ba3fe1b6f977e38f36efde2b6bfd36e4f2cfd81fdacc59159b5ba55
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
