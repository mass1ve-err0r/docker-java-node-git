FROM timbru31/java-node:11-alpine@sha256:6b3583ec122ce06f675e0e0e3e89b59d13aafa1944135d39ba9e00e74b3480b4
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
