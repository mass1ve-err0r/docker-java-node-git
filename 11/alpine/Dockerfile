FROM timbru31/java-node:11-alpine@sha256:bbc4123e8efd4ee6e438d3b257c0df7b5fe1722a575ebeb2bfe5ea779ddd4bd9
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
