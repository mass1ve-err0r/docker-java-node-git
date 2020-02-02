FROM timbru31/java-node:8-alpine@sha256:bd42e1b52035d91fef6e0d177dc91be9c5cafe9b53a636a2b20821cf09bcbdfa
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
