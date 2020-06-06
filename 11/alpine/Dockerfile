FROM timbru31/java-node:11-alpine@sha256:4976965afaff9fd6ee5c4b9c41a4afb8e29f24cce97eec8fb1c4d530fea92827
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
