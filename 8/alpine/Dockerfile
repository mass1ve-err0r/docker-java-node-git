FROM timbru31/java-node:8-alpine@sha256:e37d627b648eeb4c1084a1719c722703923fedab5a95d6c60d658c4304e8918f
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
