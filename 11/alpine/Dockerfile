FROM timbru31/java-node:11-alpine@sha256:394cc0ec112494b5c096183e7afbb77a0eb4b5b66099161e6cdb58ee962c2050
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
