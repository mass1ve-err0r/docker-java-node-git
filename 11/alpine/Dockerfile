FROM timbru31/java-node:11-alpine@sha256:b6eb3110b17fbd8478cbbc09b8d9693c8cdf148b4c94d41c59948f056aaee457
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
