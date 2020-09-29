FROM timbru31/java-node:8-alpine@sha256:72fdffad70f4c651b35a91559ed38aba4fff61d884bb3880c5cf7691c11c5ae0
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
