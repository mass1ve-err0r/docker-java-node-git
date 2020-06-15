FROM timbru31/java-node:8-alpine@sha256:aa69bbb012d78f8b5276784975426150731ed26aead7fb55da7280c4a7da4796
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
