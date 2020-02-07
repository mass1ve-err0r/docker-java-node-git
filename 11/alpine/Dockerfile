FROM timbru31/java-node:11-alpine@sha256:f909e8844a9f0165df440a003a0fe7e241724f18909720aac6ea4b1b8677adcf
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
