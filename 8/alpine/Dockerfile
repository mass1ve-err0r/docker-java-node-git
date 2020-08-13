FROM timbru31/java-node:8-alpine@sha256:db895e8c9ea933a5f8213b328099b14e2e44eb09b77653cd2fb9606ca2b552f2
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
