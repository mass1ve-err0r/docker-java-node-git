FROM timbru31/java-node:8-alpine@sha256:c7b20b3667ed38ba4cbea57fc9c517bf41ce6457414fe2e725fe2a9f4e207fe3
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
