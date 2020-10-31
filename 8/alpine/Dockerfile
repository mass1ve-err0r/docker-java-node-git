FROM timbru31/java-node:8-alpine@sha256:4a0291e6f21487e8750fc9a85c389b051f18523cb804cbf022eb800536b69c0a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
