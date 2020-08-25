FROM timbru31/java-node:11-alpine@sha256:2b08f6404df269cee15bdc7f3d708d8627a7c859a61846aeabd99848f4ed8cc3
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
