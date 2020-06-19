FROM timbru31/java-node:11-alpine@sha256:25e850b074bfedfeb9851086e854e12c8ecc6f8c664635526eaa1f6f69334175
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
