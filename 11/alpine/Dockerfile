FROM timbru31/java-node:11-alpine@sha256:33f82c4b5e34732172bc0623232b2ed9353f4913d54aba83c587562e54bf92ec
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
