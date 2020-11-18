FROM timbru31/java-node:11-alpine@sha256:bfc821b7845d84ea63a06492d00766e82846ee049fd9508eab44b78b8848df13
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
