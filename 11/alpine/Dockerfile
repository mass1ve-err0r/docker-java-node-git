FROM timbru31/java-node:11-alpine@sha256:150216b4321e8cf9020b5bbdaf56713df1414b3dade64ff8b4b48fae7d8fb033
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
