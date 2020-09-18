FROM timbru31/java-node:8-alpine@sha256:c8cf7a596a529dde636141b7c60e506cef555eef1550219d75d773f1accdd4af
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
