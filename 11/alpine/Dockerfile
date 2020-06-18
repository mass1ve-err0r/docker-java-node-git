FROM timbru31/java-node:11-alpine@sha256:ee3365bc507d54ae2c971d45c20b1e980ef2da47368fa9d56657bc7d26d0cf3d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
