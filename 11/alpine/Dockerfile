FROM timbru31/java-node:11-alpine@sha256:868ad08230e665c4b6a193df436c296fbbf9fc5bfbd19c9050dc543b10bbf611
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
