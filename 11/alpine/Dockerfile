FROM timbru31/java-node:11-alpine@sha256:92d10c2b05f0679cd876abe3f49b3ae1c4ddda7626108af69124744ebee48e0e
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
