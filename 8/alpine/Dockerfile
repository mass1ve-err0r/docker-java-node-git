FROM timbru31/java-node:8-alpine@sha256:c0cfd30d07f0db9b70b573b90231b51c6553461049f9a45544234b54e83b5557
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
