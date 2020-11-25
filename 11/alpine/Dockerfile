FROM timbru31/java-node:11-alpine@sha256:ba114c4de5e1a45bdaf42b439d6406c14064b0182468838c4466fc90d831261f
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
