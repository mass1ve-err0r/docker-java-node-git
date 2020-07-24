FROM timbru31/java-node:8-alpine@sha256:32a8969bacf6ddf5a124da2734fdb3648d5603570341b645684e4a7a805ef594
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
