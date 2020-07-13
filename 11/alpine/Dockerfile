FROM timbru31/java-node:11-alpine@sha256:eddf93ab5cd88e75babb3639dd0e76bf8971107f4cafbf0cedeaa9636b1a9410
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
