FROM timbru31/java-node:11-alpine@sha256:074e08080461df35dd6c298a48954b021a80188ba120a8a254ff8c83d2a5ee4f
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
