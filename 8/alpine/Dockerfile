FROM timbru31/java-node:8-alpine@sha256:798e1cfc4fc72688c546207cf2d032166ba358cae1995ad7f71cd18209df8949
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
