FROM timbru31/java-node:11-alpine@sha256:881a87d0a871246457326694bea8004d09aba98db2fbf052e994602715461266
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
