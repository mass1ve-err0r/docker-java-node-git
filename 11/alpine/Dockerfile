FROM timbru31/java-node:11-alpine@sha256:4aa0e91ecc4bc93df53a4c328e64cdd83edec3fb431f443b0ba7770bc38d3c51
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
