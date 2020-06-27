FROM timbru31/java-node:8-alpine@sha256:714205895960c7ab30116fed72374db2ba41251fc46bf3018b940174a16b5a94
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
