FROM timbru31/java-node:8-alpine@sha256:2c3bdcc194ab47e51fee9c1efab56bd926f2beb1e47eeb580481a6f27c753eff
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
