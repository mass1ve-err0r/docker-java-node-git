FROM timbru31/java-node:11-alpine@sha256:3ee13c21987337866e0c876ba9224ef597a93fe83df50e7934b067c1ec7691f8
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
