FROM timbru31/java-node:8-alpine@sha256:df0de690f648f11d6650c5922ae75580ba477495103c92abb09f1ee63cf404fe
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
