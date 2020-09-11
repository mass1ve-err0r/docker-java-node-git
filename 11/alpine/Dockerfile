FROM timbru31/java-node:11-alpine@sha256:75038458b488043fe9ba22379fd818358b15fbc2a859855a9d58693b5df69849
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
