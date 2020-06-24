FROM timbru31/java-node:8-alpine@sha256:715a4ef7c3a4a2cb9f8c60a15a82a4231ae49cb46004a2ef3cb442483f295051
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
