FROM timbru31/java-node:8-alpine@sha256:f8df45a29bd7d51af0b4df004d958add38ad56c7247c38006d705edbb9c45fc8
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
