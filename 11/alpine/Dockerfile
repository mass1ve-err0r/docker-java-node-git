FROM timbru31/java-node:11-alpine@sha256:c13af77a8b3f71b2440fa3679824b072fc12de51027644e8b2792dc86982c8af
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
