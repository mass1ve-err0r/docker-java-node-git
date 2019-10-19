FROM timbru31/java-node:8-alpine@sha256:d0dd0620036be29c9da4c61f17a521bf1fcceeb1c7537a15473e52b10b1cd27e
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
