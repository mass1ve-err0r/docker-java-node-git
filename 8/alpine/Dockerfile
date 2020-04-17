FROM timbru31/java-node:8-alpine@sha256:5300e03b8c2ef26236470f349d1e8e23d7ed3d139fb9139715c579d8ab50a0ad
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
