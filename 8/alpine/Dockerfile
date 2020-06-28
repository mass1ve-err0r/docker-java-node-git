FROM timbru31/java-node:8-alpine@sha256:e676479f857b1fbc17ddef38500e1218a5c890ae6e54f3568b84642587859fa4
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
