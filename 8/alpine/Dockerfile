FROM timbru31/java-node:8-alpine@sha256:563d68be6c1d032e01dc556b85abe9d36782ec1688c389fc3773bfc2d1cc5e14
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
