FROM timbru31/java-node:11-alpine@sha256:10755767ccceeb7776f14a321e22cb580a70da1c5f3403a823ecf9d982abf853
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
