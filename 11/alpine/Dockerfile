FROM timbru31/java-node:11-alpine@sha256:007ad83d1035afeab1bea6ae39a558d6d3e9f7cec19d2ab17e19ff55eac975f4
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
