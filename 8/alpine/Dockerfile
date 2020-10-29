FROM timbru31/java-node:8-alpine@sha256:0390d030d3f7581eaf35233cefea073dcc61a1a3f85b2261ca34ed1cd678fd9e
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
