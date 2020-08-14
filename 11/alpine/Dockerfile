FROM timbru31/java-node:11-alpine@sha256:931e5bdcc5405163c3724e8fdc2a39e9b08be99e7c81ed423d1c6eed644a70ac
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
