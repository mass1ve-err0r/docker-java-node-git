FROM timbru31/java-node:11-alpine@sha256:d2786042d762e12c4452264c6193ff2f4efd33923d40765ae9a069ded372e6f0
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
