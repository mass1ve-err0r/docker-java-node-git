FROM timbru31/java-node:11-alpine@sha256:6059eb858dd07f5df55be0fb9ed52f563658724f1f7f04585c37a3a13749726d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
