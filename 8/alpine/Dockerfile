FROM timbru31/java-node:8-alpine@sha256:fc8b257e8acb31223908a59a8503f98cc895669a95e82af2140f631dc629ea73
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
