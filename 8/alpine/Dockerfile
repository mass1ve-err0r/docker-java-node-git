FROM timbru31/java-node:8-alpine@sha256:79c3f5221aada15f74e107b9aff44ed0c530a84d7fad13962156f46a7fe287db
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
