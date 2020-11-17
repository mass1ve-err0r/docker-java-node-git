FROM timbru31/java-node:8-alpine@sha256:ba8cc1febe8c62cb3786fc3ca67feebe82cb1a13f32c9e1e2b507db8d63d55f9
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
