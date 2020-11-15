FROM timbru31/java-node:8-alpine@sha256:197225952e3a3daf23c4d7a30d23b62e35d9cbfc32b4b0d65b09629891f3a330
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
