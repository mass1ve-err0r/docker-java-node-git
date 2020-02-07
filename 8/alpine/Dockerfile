FROM timbru31/java-node:8-alpine@sha256:6f1e15d51f78f83523b3e7675cdae3b2dfc004d9b0cd2f4e91a7da7ad57368c4
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
