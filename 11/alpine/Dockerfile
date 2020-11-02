FROM timbru31/java-node:11-alpine@sha256:7c69729464dcdda2624dcfe12af48ef5dac14ca819367e57707782837109b867
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
