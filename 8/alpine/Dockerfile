FROM timbru31/java-node:8-alpine@sha256:69b28c4e5bd0168632194e88958e11d019938a4515c0a58d4f8ca70c747a7f5c
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
