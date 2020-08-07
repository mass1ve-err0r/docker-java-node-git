FROM timbru31/java-node:11-alpine@sha256:f2fbe2d4dc85fbc3353841c5d4e1ed3c8ead6aa08d795e87dd8f8499ffa2c96a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
