FROM timbru31/java-node:11-alpine@sha256:83e8c4e9641d436f574395f2ee80e30f740e8056c54b266afd2e445f71da3c03
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
