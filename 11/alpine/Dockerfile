FROM timbru31/java-node:11-alpine@sha256:12d5f862de94c6dcb82a60e85f41750eb8196f82e2c6e7c3dd74c8aa630c8b26
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
