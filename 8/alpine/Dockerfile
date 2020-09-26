FROM timbru31/java-node:8-alpine@sha256:2ddaba00fe980193f30fd8fb21494b7925c06bf8047a56d84dbf8a88d0a0b77d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
