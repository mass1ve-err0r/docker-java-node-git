FROM timbru31/java-node:11-alpine@sha256:3021206e1143934b24df1c3cc982dac4850cee7e720039c79076df089819a7df
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
