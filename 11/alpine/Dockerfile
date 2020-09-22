FROM timbru31/java-node:11-alpine@sha256:b987b1feece3efc326a230cc615263f2b35a20de8719fc7708fa752e4840dd6f
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
