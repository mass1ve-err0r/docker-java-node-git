FROM timbru31/java-node:8-alpine@sha256:2d7a850e966da3bd2baa301d7f328923113f46815b6c5979a212af9a9cd26c2b
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
