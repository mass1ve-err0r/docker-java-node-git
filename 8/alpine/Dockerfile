FROM timbru31/java-node:8-alpine@sha256:d011e469f32add778da760e8738353ab4ddc6aef6852712eee9d898d133ae622
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
