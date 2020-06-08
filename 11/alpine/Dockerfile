FROM timbru31/java-node:11-alpine@sha256:941c83793c397be53f485dcf307470192a4f222a9bee03db3332c43ca54354a4
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
