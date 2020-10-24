FROM timbru31/java-node:8-alpine@sha256:ee18075f57378ef87ecac7574848694aca8d7ce9b98ad0b2f9128e33067a5cda
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
