FROM timbru31/java-node:11-alpine@sha256:6fd85ed74aeda3eef15dcafc0cef12224b00cdc8fe7d3815f0353bbe49112954
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
