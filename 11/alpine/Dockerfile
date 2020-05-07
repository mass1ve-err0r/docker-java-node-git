FROM timbru31/java-node:11-alpine@sha256:d7c67b3118d795c8b377801adc356900f53d180178cd107620bede47803b9985
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
