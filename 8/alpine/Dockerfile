FROM timbru31/java-node:8-alpine@sha256:284f8107d4798b6367a9f344b95dc9b2f3c429ca16d40481f011edead241228a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
