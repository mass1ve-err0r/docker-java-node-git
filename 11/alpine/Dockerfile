FROM timbru31/java-node:11-alpine@sha256:4cdd4b14634bc0fe3b05e6d27c085248be2fbdcf608922f020273acf3b16fc65
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
