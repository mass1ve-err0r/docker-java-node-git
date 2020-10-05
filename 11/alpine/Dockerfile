FROM timbru31/java-node:11-alpine@sha256:ada5d7cab3a464176e85f9975c526139841bdc8b9c6d08b4f5ef9b3e5cbf7862
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
