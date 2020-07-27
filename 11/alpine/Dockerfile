FROM timbru31/java-node:11-alpine@sha256:d68d7019278569de8a57c41c6204403d6f06a3624c3334e1d378a6614bb7b0c2
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
