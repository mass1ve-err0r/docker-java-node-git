FROM timbru31/java-node:8-alpine@sha256:c61e1bec07b2b2cbd9b008b7090cc46652ceb43b55f6a5cfa97a05b86855cd8d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
