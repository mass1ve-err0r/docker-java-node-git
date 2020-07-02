FROM timbru31/java-node:11-alpine@sha256:73a072602fd7e814c685da75571393b63e3a3ded56007a24263be657af25f8d4
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
