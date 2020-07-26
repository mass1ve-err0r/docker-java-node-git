FROM timbru31/java-node:8-alpine@sha256:e548d69e5203621fdde6072a7f32c38e79f3aa9ca20ccec12da59830f91f4564
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
