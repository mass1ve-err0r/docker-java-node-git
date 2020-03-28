FROM timbru31/java-node:11-alpine@sha256:add7ed6fd63468eda91fefce6617ffaf05699781acc935f865b72d278abdc113
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
