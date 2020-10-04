FROM timbru31/java-node:8-alpine@sha256:057ed8075d7c9e1e03e54199d775a13732e615a97e6b7f07d0f229bd35d2cb9e
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
