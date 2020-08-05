FROM timbru31/java-node:8-alpine@sha256:dd4b419082eedfad9371822d751703956c27211e8dd2f55fc81c487849108ed8
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
