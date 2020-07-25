FROM timbru31/java-node:11-alpine@sha256:a852450c46d66fd1d800fb73bb8dd8437d0fa0f4e8d5f826c0817d21d49c4b0f
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
