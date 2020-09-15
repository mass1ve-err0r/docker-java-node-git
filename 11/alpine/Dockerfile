FROM timbru31/java-node:11-alpine@sha256:de4584bd43ef98691c1f2d469f1e47ff0168d6a3f74b9e808da6095658edafed
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
