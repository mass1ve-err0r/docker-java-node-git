FROM timbru31/java-node:8-alpine@sha256:81af93647cfe7c891fec0cdf15ec1a6082fa82de73261b416056d853058b7040
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
