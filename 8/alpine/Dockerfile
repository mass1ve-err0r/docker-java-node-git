FROM timbru31/java-node:8-alpine@sha256:fefc286a64d24280fade323f2c3534c500f5801a7c6beb16d6512434a8694429
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
