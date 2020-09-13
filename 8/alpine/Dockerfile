FROM timbru31/java-node:8-alpine@sha256:626a9700f241473773e65d445b737ae6a11a161b185440f8ec0577b1460928fc
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
