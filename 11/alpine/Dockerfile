FROM timbru31/java-node:11-alpine@sha256:098d536b97554880939eecea9e6204cbf956f67aa3fa8e2cff489a191e00eca6
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
