FROM timbru31/java-node:8-alpine@sha256:5a7b5094205164aa02d88e634a6ee1d42917dfa619b9e3edf8a09d3d832fa24e
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
