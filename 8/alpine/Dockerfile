FROM timbru31/java-node:8-alpine@sha256:1452eabdde512bc9608cb05cfb21699072d661291c36836353efabbb781e0d01
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
