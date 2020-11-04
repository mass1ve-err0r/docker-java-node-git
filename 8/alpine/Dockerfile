FROM timbru31/java-node:8-alpine@sha256:ee6e37ef62f8aeba4037b33c11d1799828451aa19fbab989b118cadad322eccc
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
