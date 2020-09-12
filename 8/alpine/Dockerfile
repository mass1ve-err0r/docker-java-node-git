FROM timbru31/java-node:8-alpine@sha256:51c4aae80d6e04ec368139d30f07497aea0483c793ccc3415922fa07e1241045
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
