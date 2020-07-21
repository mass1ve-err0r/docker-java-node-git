FROM timbru31/java-node:8-alpine@sha256:4b9028686ed0b85be41679053f611e99cceb3bd5f9119727eaa99ee756b85a57
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
