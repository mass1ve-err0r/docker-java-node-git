FROM timbru31/java-node:11-alpine@sha256:546bc9328a05ce6840fec49b8eb621379459ddafaad01ce4f6f2c20d4a8c668f
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
