FROM timbru31/java-node:8-alpine@sha256:99d863db84e20c40c487e4ba5d2fc710fb2077e7435e687eeaaac306b03cffc5
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
