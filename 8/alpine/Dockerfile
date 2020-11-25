FROM timbru31/java-node:8-alpine@sha256:b7048ff2da1af9e51cb6276705cd77623d48468711a130416069fbc0e86174b2
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
