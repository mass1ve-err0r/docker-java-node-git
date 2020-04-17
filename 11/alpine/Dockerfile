FROM timbru31/java-node:11-alpine@sha256:f67281d7dea76be394f778ef173f5d276c8fa6b7a963fd4291be559a3105048c
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
