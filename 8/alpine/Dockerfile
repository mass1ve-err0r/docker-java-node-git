FROM timbru31/java-node:8-alpine@sha256:89e0972deb982048a6e2dd64dacb94d522ad10f49a52db22e2ea18dffee37492
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
