FROM timbru31/java-node:11-alpine@sha256:ab92124bf2d0de2edb2aa18dd92c35c9a594c9c4d292fac502e85d7f78f4f135
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
