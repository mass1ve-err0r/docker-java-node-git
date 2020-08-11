FROM timbru31/java-node:11-alpine@sha256:da70d888f4c67224ff63b982398b6889e5f640292d4e5c907a7c958339ebb077
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
