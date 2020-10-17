FROM timbru31/java-node:11-alpine@sha256:edad5ab2365af992d298c679baa060fe5483750928ce7882aa419b4e058a4381
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
