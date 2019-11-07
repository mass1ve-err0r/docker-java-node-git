FROM timbru31/java-node:8-alpine@sha256:c31805049d4a1437328fa07daad1fdfe0c017877fb85c3bf6118b5bbb8750e11
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
