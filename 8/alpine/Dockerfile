FROM timbru31/java-node:8-alpine@sha256:f4dd1ff232d9a18cbb34795bd8e72a233f2eff9eaf18de0ca67b054b000081c9
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
