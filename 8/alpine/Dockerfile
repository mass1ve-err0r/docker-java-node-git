FROM timbru31/java-node:8-alpine@sha256:ad40ed892d96e68920d5182f2b6ab57d4cabb9a14fda33e516c26848a76b24ea
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
