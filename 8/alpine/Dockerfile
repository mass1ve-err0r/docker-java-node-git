FROM timbru31/java-node:8-alpine@sha256:07c20818566f677d3e8d2404f60d45d4e48ee59593fe97a4bc5974ef7b30388a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
