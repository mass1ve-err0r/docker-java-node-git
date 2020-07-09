FROM timbru31/java-node:8-alpine@sha256:ffcc84c9c617caf4c8d9f3b084ef1355f4e913717ea721bbff0db46b26a34b21
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
