FROM timbru31/java-node:8-alpine@sha256:0fc8ba86734b2e3eb11b6ff93fcbd380907582c9c7074c69b068ea1432ff1239
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
