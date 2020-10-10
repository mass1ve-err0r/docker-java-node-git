FROM timbru31/java-node:11-alpine@sha256:b8e5dc1459a60cea4e0c316ba09f05370f1cc5cae2e7c8828682ec9254853178
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
