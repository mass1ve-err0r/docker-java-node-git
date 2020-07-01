FROM timbru31/java-node:11-alpine@sha256:97c139c39c9b3861f7a84a3aa5f922e866faef31c8ff72447e5404613ea58746
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
