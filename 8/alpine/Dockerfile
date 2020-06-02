FROM timbru31/java-node:8-alpine@sha256:dbd18b2e1e0528844dde7d1d5ff05fa9906bb74fb5dc85eb3329a823e67297bc
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
