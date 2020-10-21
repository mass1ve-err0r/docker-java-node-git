FROM timbru31/java-node:8-alpine@sha256:69eaf01f9bd38454e556f5bf4048852a73a42651f09fe0f71aca9fe74e515cef
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
