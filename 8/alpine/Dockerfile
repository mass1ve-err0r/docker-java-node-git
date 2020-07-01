FROM timbru31/java-node:8-alpine@sha256:f33009a9d9b02cbdb422c90a6f1ceb4d003407318196b99852a6648268a427b2
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
