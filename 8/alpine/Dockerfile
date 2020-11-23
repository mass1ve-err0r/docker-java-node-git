FROM timbru31/java-node:8-alpine@sha256:10b5f210e0919817ec2dbe9e28268c60b4f24415a09562bb8766855b3788cb50
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
