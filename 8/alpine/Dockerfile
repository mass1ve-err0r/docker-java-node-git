FROM timbru31/java-node:8-alpine@sha256:86892a717d2df097f31072e47fdb52aee8d98256ec30157980dbaa548a230745
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
