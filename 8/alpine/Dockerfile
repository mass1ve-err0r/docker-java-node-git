FROM timbru31/java-node:8-alpine@sha256:eba92df4ce09f794bd06735602381f410eec7aecaf7e1eda1bf4ce442d25e4ca
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
