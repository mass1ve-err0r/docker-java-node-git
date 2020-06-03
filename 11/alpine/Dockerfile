FROM timbru31/java-node:11-alpine@sha256:73f7f23e996c7c290a85e7d3ba94ca065cd841e117695b45f19c2840043e19c9
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
