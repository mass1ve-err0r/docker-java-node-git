FROM timbru31/java-node:11-alpine@sha256:84aa8219a7fc6aac081ad1696cc152620f1c51d7bb1196c02786dcef42ccdc70
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
