FROM timbru31/java-node:8-alpine@sha256:adec7f7b7b6863d7b5257d3450b3edc8aa2218009dfa33837f6e4ba4cc7b9f5a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
