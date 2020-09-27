FROM timbru31/java-node:11-alpine@sha256:983b1fd053294211b1a958a433043a8b60b8bc07f0862e33b5462ca6094416cd
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
