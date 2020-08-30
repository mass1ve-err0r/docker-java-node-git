FROM timbru31/java-node:11-alpine@sha256:ce38ff50a9f23aeb0993bb524df213c65aae1dae3951df1a52a42c6b8d1c028d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
