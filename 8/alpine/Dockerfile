FROM timbru31/java-node:8-alpine@sha256:93a3d8ff0156ba852c155b743cc2734d63aaace71aaf33fe97fad49920717166
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
