FROM timbru31/java-node:11-alpine@sha256:c6432194e398b228737115410f335ff7017d880aff841037c6a47447d014a414
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
