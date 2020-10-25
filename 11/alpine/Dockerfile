FROM timbru31/java-node:11-alpine@sha256:df7d3126dafedfdface20b6baf88866b8571c2ee4fa04745a50bc30af3de5fa8
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
