FROM timbru31/java-node:8-alpine@sha256:58da496fa5133fbf984a07ca5410b15cd120969c87b73e451579a409726367d6
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
