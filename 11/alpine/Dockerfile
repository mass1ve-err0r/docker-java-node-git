FROM timbru31/java-node:11-alpine@sha256:79cf4306b95512695dc0e36b528a1d4c88732c43a6cd548f65e8a62b7035016e
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
