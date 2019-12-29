FROM timbru31/java-node:8-alpine@sha256:a39772801cdbe53521f708cc516011cb2eb025f2393c7e449e44185fc629f01e
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
