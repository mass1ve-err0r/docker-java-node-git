FROM timbru31/java-node:11-alpine@sha256:9172af4a20f90dc122916a36f763f7d825fe2abb7acaa495141df8347b676e55
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
