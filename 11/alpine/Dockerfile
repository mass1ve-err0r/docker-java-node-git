FROM timbru31/java-node:11-alpine@sha256:675d876055701d08d5d0b75c65969e0fa71d4a27cc9cf616f17c2048b68fd86e
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
