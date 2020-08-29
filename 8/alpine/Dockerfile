FROM timbru31/java-node:8-alpine@sha256:034601c7cbd03cdee79bb6a9b6abb6f563979887b08bdfca75b7af960252a214
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
