FROM timbru31/java-node:11-alpine@sha256:430fadde9fb1b6b85421d9ff5bbcf40e8c40e982017a91244e51e449dc09a787
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
