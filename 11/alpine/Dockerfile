FROM timbru31/java-node:11-alpine@sha256:77bb565926b92c85747997b5c1720e30b6ae485aad2713604f342168d0d25251
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
