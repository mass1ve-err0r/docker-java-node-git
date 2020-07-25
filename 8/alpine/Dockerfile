FROM timbru31/java-node:8-alpine@sha256:5646d77f6a32b4a124122f8cb2dc3e65d6a773da8317d74744376355e88e22fb
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
