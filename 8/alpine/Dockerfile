FROM timbru31/java-node:8-alpine@sha256:0b710de8614ba8085fe1052e5412cd7628407593e46c87c3992b1ff77549f50a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
