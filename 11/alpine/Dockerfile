FROM timbru31/java-node:11-alpine@sha256:f5a85b27ffd0f7f4a9269cb4f3eac597652fb9cb306842d7c678d28476f19039
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
