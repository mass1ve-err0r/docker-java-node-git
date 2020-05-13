FROM timbru31/java-node:8-alpine@sha256:6b496d73297ce863d1902761930208f0efbeba312292287987342dac80444f71
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
