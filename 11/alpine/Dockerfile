FROM timbru31/java-node:11-alpine@sha256:9fe6ffe7a423c75eb2fa22c27126064718b2f4dffabe01a4da105ce2ad28b8cd
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
