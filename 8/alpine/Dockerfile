FROM timbru31/java-node:8-alpine@sha256:70074bc61f6e1762392df7d10b7c61f0827d80da881a1682267f21bf9b6d112b
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
