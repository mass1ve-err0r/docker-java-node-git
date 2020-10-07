FROM timbru31/java-node:11-alpine@sha256:2894f3da355c0d6246d6e801aef3f1c032b86d7aa5f42b8200a6cd0057f090cf
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
