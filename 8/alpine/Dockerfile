FROM timbru31/java-node:8-alpine@sha256:00100a0ecff3ade92440102eb375432046917cf8e61068c90d8c7d83f1865f7a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
