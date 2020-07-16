FROM timbru31/java-node:8-alpine@sha256:19791e1a0181ff7d5f12767e958892f13cd6c53a4dea62b55fb8f0c96dfecf8f
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
