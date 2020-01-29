FROM timbru31/java-node:8-alpine@sha256:2152f578eedf6f0a537e888af50c77fabebce42c6d4d5c101f88177c3df189e7
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
