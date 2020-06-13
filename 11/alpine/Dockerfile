FROM timbru31/java-node:11-alpine@sha256:79201929e61aadb3e42583fdf458ec5fe0683c8d935764d6ec34005db15b912e
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
