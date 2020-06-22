FROM timbru31/java-node:8-alpine@sha256:4fe145f3d95f6cb2cbd8990e9763148d14c4c250ffdce121e9831ab814c4c01f
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
