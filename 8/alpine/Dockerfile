FROM timbru31/java-node:8-alpine@sha256:b8b08da090c1fee5ff522a44addfc4549962267e5ff500f6510e5bfd2a6e18e2
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
