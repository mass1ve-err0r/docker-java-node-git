FROM timbru31/java-node:8-alpine@sha256:ee166a19d7223e83957e4ccfe068377c7714b8ca0c9b908105628cd4216975e4
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
