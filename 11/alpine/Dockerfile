FROM timbru31/java-node:11-alpine@sha256:461c7f8ba4ff914eead18b24f94eb8da239d114a5dfd4d9b91ebfb3ffd2cca9a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
