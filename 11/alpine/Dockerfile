FROM timbru31/java-node:11-alpine@sha256:c00c0a2c4a1f764d1fef631351c249417157696d31219cbc4597c3228f9965f6
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
