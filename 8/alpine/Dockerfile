FROM timbru31/java-node:8-alpine@sha256:75ee72f03b0904590461c5d0bcb41f81bbc1dbedb8099a6f889595e5aaaf819e
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
