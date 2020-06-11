FROM timbru31/java-node:11-alpine@sha256:ffe94eb0a0f5c370f6f65603e4e0e2cd9708bc622b96300c8ac13bc198a0a92a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
