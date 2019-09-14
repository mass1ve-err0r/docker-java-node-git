FROM timbru31/java-node:11-alpine@sha256:a0b815abe782e17ef35c9a76eac6fab3ba9e031645203620b20beb956e5ce9b6
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
