FROM timbru31/java-node:8-alpine@sha256:d478b7c9d8bf15b03e75f134f7b5e2b11438736cbef3ade516247d9066db629f
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
