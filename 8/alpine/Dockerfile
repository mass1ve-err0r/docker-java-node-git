FROM timbru31/java-node:8-alpine@sha256:32cb4d934e66b5e226e43b710e26647cb79658385d93cd7baa8dcb5d17db6073
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
