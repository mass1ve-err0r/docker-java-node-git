FROM timbru31/java-node:8-alpine@sha256:0bb293562c719e23e16d10216c79db584d6f9216b46634c8bebe441afa600287
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
